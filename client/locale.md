# 本地化翻译

[XNA CNCNet Client CN](//github.com/YR-Client-Team/xna-cncnet-client-CN)
拥有本地化功能, 请参照[它是如何工作的](#它是如何工作的)

若您想参与翻译项目, 请参照[我应该怎样创建.lang文件](#我应该怎样创建.lang文件)

## 它是如何工作的

在[XNA CNCNet Client CN](//github.com/YR-Client-Team/xna-cncnet-client-CN)的项目中存在
一个叫做ClientLocale的小项目, 它复制主要的翻译逻辑

### `Init(string, string, string)`

初始化本地化逻辑

```csharp
public static LocaleResource Init(
    string localeFolderPath,
    string locale,
    string failbackLocale = "en"
);
```

|类型|参数|作用|默认值|
|-|-|-|-|
|`string`|`localeFolderPath`|指定本地化文件目录||
|`string`|`locale`|本地化文件名||
|`string`|`failbackLocale`|失败时使用的本地化文件名|`"en"`|

它在初始化时会读取`localeFolderPath`路径下的`$"{locale}.lang"`文件  
这个文件是一个Json格式的文件  
程序会反序列化它为一个Map集合(`Dictionary<string, string>`)并存放到私有成员中  

在获取本地化字符串资源时只需要引用名称空间`ClientLocale`即可使用扩展方法

```csharp
public static string GetLocaleString(this string key);
public static string GetLocaleString(this string key, params object[] args);
```

### `GetLocaleString(this string)`

它有一个参数, 使用时直接调用即可`"key".GetLocaleString()`  
它将返回本地化字符串

### `GetLocaleString(this string, params object[])`

它有两个参数, 第一个参数作用与它的另一个重载作用相同  
第二个参数用于`string.Format()`  
您可以轻松的使用这样的方式来格式化字符串

```csharp
// "Key": "这是一个{0}本地化字符串{1}"

"Key".GetLocaleString("arg1", "arg2");

// "这是一个arg1本地化字符串arg2"
```

## 我应该怎样创建.lang文件

.lang文件是一个json格式的文件, 您可以使用文本编辑器直接打开它  
.lang文件的编码格式应为**UTF-8**, 这有利于全球化  

.lang文件的结构如下

```json
{
    "key1": "value1",
    "key2": "value2"
}
```

虽然这个key可以是任何字符串, 但我们人为限定这个key应遵守以下规则:

- 应用帕斯卡命名规则(PascalCase)
- 不允许出现空白字符(包括空格 制表符 纵向制表符 回车符 换行符)
- 不允许出现非ASCII字符
- 不允许出现除"."以外的符号(包括_ - ! @ # $ % ^ & * 等)

您在命名key的时候应考虑以下问题:

- 这条字符串是什么功能在用?
- 这条字符串将显示什么内容?

举个例子:  
有这样一个字符串  
`"key": "在{1}处找不到{0}"`(`"Cannot found {0} at {1}"`)  
在程序中使用方式如下

```csharp
Logger.Log("key".GetLocaleString(fileName, folderPath));
```

则此时 您的key应命名为"Log.NotFound0At1"

在创建键值对时, 您需要注意以下几点:  

- 在`en.lang`中创建相同的键值对, 用于其他语言翻译
