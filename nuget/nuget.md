# Nuget包管理

Nuget包是一种现代的dotnet依赖方案  
引用Nuget包, 您无需去另外下载, nuget会自动帮您下载您需要的程序集

## YR-Client-Team Packages

这是一个团队包源, 您可以通过
`dotnet nuget add source -n "YR-Client-Team Packages" -u <Your Github Username> -p <Your Github Account Token>`
指令去添加一个Nuget源

## Push Nuget包到YR-Client-Team Packages

!> 您需要先[添加YR-Client-Team Packages Nuget源](#YR-Client-Team_Packages)

0. 首先, 确保您的项目文件中写上了`RepositoryUrl`属性  
1. 然后, 通过`dotnet pack [<PROJECT>]`命令打包您的项目  
2. 最后, 使用`dotnet nuget push <Your .nupkg File> -s "YR-Client-Team Packages"`命令上传您的Nuget包

?> 您可以使用通配符, 如:`dotnet nuget push *.nupkg -s "YR-Client-Team Packages"`

## 从YR-Client-Team Packages上下载Nuget包

!> 您需要先[添加YR-Client-Team Packages Nuget源](#YR-Client-Team_Packages)

?> 使用`dotnet add [<PROJECT>] package <Package Name> [-v <VERSION>]`添加包到项目引用  

?> 使用`dotnet restore [<PROJECT>]`命令还原Nuget包  
