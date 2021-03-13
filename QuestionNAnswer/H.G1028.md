## 复仇时刻RN 0.99.G1028内测版 更新说明

***

## 复仇时刻RN 0.99.G1013B内测版 更新说明
* 修正了上一版内测在任务战役中导致频繁crash的问题；
* 修正了上一版内测盟1狙击手无法攻击尤里的问题；
* 优化了浮岛要塞地图的布局；
* [Adjustment#66]韩国黑鹰战机燃烧弹头更换新的动画素材（By 小星星），对建筑的杀伤大幅提升；
* [Adjustment#107]英国狙击手部署武器弹头动画替换。

***

## 复仇时刻RN 0.99.G1013内测版 更新说明
* [Bug#147]苏军米格战机对装甲单位的伤害进行了下调，大幅削弱对基地车载具的影响，对矿车进行了削减；
* [Bug#211]修复了主线盟3任务平定装置，建造动画播放两次的问题；
* [Bug#222]修复了群测版本开始，AI尤里钻地车鬼畜Bug；
* [Bug#217]修正了磁能坦克和磁暴步兵会主动给磁暴线圈充能无法正常攻击的问题；
* [Bug#146]AI在全体冲锋状态时，归属该AI的条顿坦克残骸会响应指令，这将不再发生； 
* [Bug#223][Bug#227][Bug#184]群测版本之后的苏军AI武直部署状态不正常，现已修正；
* [#168]AI派遣步兵进入敌方战斗碉堡后，碉堡可能因为AI战败而强制变卖。现在碉堡将不再能被非法变卖；
* [Adjustment#66]韩国黑鹰战机武器机制调整，主武带有范围三格的燃烧弹头，经过的单位将会受到持续灼烧；
* [Adjustment#107]英国狙击手增加部署攻击模式，部署后攻击显形，对射速增快但是命中率略低；对步兵伤害与非部署形态持平，重甲和建筑较弱，轻甲较大，观察员依然提供三倍加成；
* [Adjustment#130]新城市地表（UrbanNew）地形引入新增的柏油路相关地块；
* [Adjustment#127]月球地形新增水泥悬崖套装；
* [Adjustment#129]新城市地表（UrbanNew）引入斜坡河堤元素，适用浮岛地图；

***

## 复仇时刻RN 0.99.G0824内测版 更新说明
* [Bug#203]修复了窗口化游戏时，滑条控件漂移的问题；
* [Adjustment#83]引入新判定机制，允许仅将小队的第一个载具单位视为运输器，以解决存在多个可作为运输器的载具混编时的问题；
* [Bug#136]修正了光棱镜分队进入圣骑士机甲会导致崩溃的问题；
* [Adjustment#124]，[Bug#211]新盟三任务中，平定装置的建造机制完善，同时增加了实际的平定装置功能，范围25格的敌军单位将无法开火； 
* [Adjustment#108]修正了更换后的法国气象塔雪地闲置动画影子Bug；
* [Bug#174]减少了AI载具携带工程师的数量；
* [Bug#12]修正了读取存档后会导致被禁止的AI建筑和飞行器克隆又被开启；
* [Bug#196]修正了德国灰熊uc对防御类建筑伤害异常的问题；
* [Bug#165]新苏联1紫色所属方会训练毒蝎坦克与赤炎坦克；
* [Adjustment#9]现在英国圣骑士战甲存在护盾时免疫心控 盾消失时能被心控；
* [Adjustment#123]新增苏俄天降红潮技能，三架次飞机，包含动员兵、防空步兵、磁暴步兵、防空履带车、恐怖机器人；
* [Bug#206]在重工生产了攻城机甲后，会导致集结点地块不允许建造并且通过，这将不再发生；
* [Bug#209]新苏联1任务中，有一处悬崖会导致单位遁地，这将不再发生；
* [Bug#204]圣骑士机甲在有护盾时将不再能被恐怖机器人寄生攻击，但无盾时可被攻击；
* [Bug#216]利刃召唤的机械单位可被警犬攻击并消灭，这将不再发生；

***
## 复仇时刻RN 0.99.G0726P更新说明
* 重构了RE(reconnection error)收集机制的文件写入，恢复了旧版方式的内容写入
* 本次启动器更新将会尝试自动给Win7 及以上用户的 RA2MD.EXE YURI.EXE RunRN.EXE GameRN.EXE GameMD.EXE获取管理员权限，并给GameRN.EXE GameMD.EXE设置16色
* [Bug#138]在之前的版本中，一些建造速度较慢的建筑，在保存再读取存档之后，速度会变的异常快，现在这个问题不再会发生
* [Bug#132]英国观察员召唤的智能炸弹可以被铁幕和立场护盾影响，这将不再被允许
* [Bug#123]尤里空投炸弹之前可以被神经突击毒气影响，现在不会再受到影响
* [Bug#195]古巴自爆飞机出厂时会出现在盟军的停机平台上，而不受停机平台机位控制，现在盟军停机平台不再允许生产出自爆飞机
* [Bug#58]光棱坦克反甲能力下调至原来的一半（恢复到原版YR数值），移动攻击能力得到保留
* [Adjustment#108]法国气象塔补上了雷暴技能的环境云层动画，同时修正了闲置动画不连续的问题
* 修正了内测盟军第三关任务目标一完成后，援军中的圣骑士战甲无法正确登场的问题
* 修正了有时AI的特殊小队会导致游戏崩溃的问题（建筑目标编写错误）
* 针对AI工程师小队进行微调，增加了AI消除冗余工程师单位的措施
* 对苏军第一关任务的AI小队进行了调整

***

## 复仇时刻RN 0.99.G0615P3更新说明
* 修正了RE(reconnection error)收集机制的文件写入错误

***
## 复仇时刻RN 0.99.G0615P2更新说明

* [Bug#188]联机时古巴的自爆飞机被击落会造成崩溃和断线
* 加强了对RE(reconnection error)问题的信息收集机制

***

## 复仇时刻RN 0.99.G0615P1更新说明

* [Bug#167]修正了苏系阵营的国家存在核能反应堆时，被摧毁无法判定该所属方失败的Bug

***

## 复仇时刻RN 0.99.G0615P更新说明（编写中）
本次更新的重点内容（包括但不限于）：
1. 启动器显示版本号，支持自动更新
2. 修复若干F1028版本的任务无法通关问题
3. 新增法国气象塔建筑（屏蔽粉碎大炮）
4. 古巴kbfz改为伪装渗透单位，新增荣耀战士
5. 全局AI重写(欢迎挑战!)
6. 开放主线任务盟军第三关(非最终版本)

本次更新具体内容：
1. 修正[Bug#61]：苏军任务1-红色沙文，逮捕将军后无法通关；
2. 修正[Bug#45]: TR旧任务尤里第一关，心灵信标部署无效果，任务四无法达成，卡关；
3. 修正[Bug#67]: TR旧任务-盟军黑森林开局核弹爆炸时导致crash。
4. 修正了[Bug#76]，敌友关系发生改变时可能导致敌方隐形单位直接可见
5. 修正了[Bug#81]，12.31反馈的crashdump，与部分武器伤害判定有关联
6. 修正了[Bug#79]，满血的建筑可能会残留维修扳手状态
7. [Adjustment#20]；启动器上可以显示当前版本号
8. [Adjustment#33]：中立方钻矿设备默认设置为可被占领
9. [Bug#73]：加强烈焰核心，速度4，HP1400，自毁状态免疫心控
10. [Bug#74]：苏1任务调整，友军颜色改为深红，伊文重合修正，部分布局调整
11. [Bug#48]：地图-骑马天堂修正地形错误和科技建筑摆放错误
12. [Bug#66]：尤里钻地突击车平地运动和钻地运动模式选择不明确修正
13. [Bug#83]：石油大亨模式中古巴/法国无法顺利延伸科技树
14. [Bug#82]：修复盟军掷弹兵攻击时可能导致crash
15. [Bug#71]：照明灯赋予了少量视野，但仅能显示探照灯本身
16. 启动器重构，修复了稳定性问题。
17. 完成古巴荣耀战士设定。
18. 尤里T4兽人三兄弟狂暴分子完成（音效待更新）。
19. 盟军暴风摩托数据和音效完成。


[Bug#12]:https://github.com/Zero-Fanker/RN_All_Issues/issues/12
[Bug#45]:https://github.com/Zero-Fanker/RN_All_Issues/issues/45
[Bug#48]:https://github.com/Zero-Fanker/RN_All_Issues/issues/48
[Bug#58]:https://github.com/Zero-Fanker/RN_All_Issues/issues/58
[Bug#61]:https://github.com/Zero-Fanker/RN_All_Issues/issues/61
[Bug#66]:https://github.com/Zero-Fanker/RN_All_Issues/issues/66
[Bug#67]:https://github.com/Zero-Fanker/RN_All_Issues/issues/67
[Bug#71]:https://github.com/Zero-Fanker/RN_All_Issues/issues/71
[Bug#73]:https://github.com/Zero-Fanker/RN_All_Issues/issues/73
[Bug#74]:https://github.com/Zero-Fanker/RN_All_Issues/issues/74
[Bug#76]:https://github.com/Zero-Fanker/RN_All_Issues/issues/76
[Bug#79]:https://github.com/Zero-Fanker/RN_All_Issues/issues/79
[Bug#81]:https://github.com/Zero-Fanker/RN_All_Issues/issues/81
[Bug#82]:https://github.com/Zero-Fanker/RN_All_Issues/issues/82
[Bug#83]:https://github.com/Zero-Fanker/RN_All_Issues/issues/83
[Bug#123]:https://github.com/Zero-Fanker/RN_All_Issues/issues/123
[Bug#132]:https://github.com/Zero-Fanker/RN_All_Issues/issues/132
[Bug#136]:https://github.com/Zero-Fanker/RN_All_Issues/issues/136
[Bug#138]:https://github.com/Zero-Fanker/RN_All_Issues/issues/138
[Bug#165]:https://github.com/Zero-Fanker/RN_All_Issues/issues/165
[Bug#167]:https://github.com/Zero-Fanker/RN_All_Issues/issues/167
[Bug#174]:https://github.com/Zero-Fanker/RN_All_Issues/issues/174
[Bug#188]:https://github.com/Zero-Fanker/RN_All_Issues/issues/188
[Bug#195]:https://github.com/Zero-Fanker/RN_All_Issues/issues/195
[Bug#196]:https://github.com/Zero-Fanker/RN_All_Issues/issues/196
[Bug#203]:https://github.com/Zero-Fanker/RN_All_Issues/issues/203
[Bug#204]:https://github.com/Zero-Fanker/RN_All_Issues/issues/204
[Bug#206]:https://github.com/Zero-Fanker/RN_All_Issues/issues/206
[Bug#209]:https://github.com/Zero-Fanker/RN_All_Issues/issues/209
[Bug#211]:https://github.com/Zero-Fanker/RN_All_Issues/issues/211
[Bug#216]:https://github.com/Zero-Fanker/RN_All_Issues/issues/216
[Adjustment#9]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/9
[Adjustment#20]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/20
[Adjustment#33]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/33
[Adjustment#83]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/83
[Adjustment#108]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/108
[Adjustment#123]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/123
[Adjustment#124]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/124