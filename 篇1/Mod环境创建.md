Mod环境的配置

要想写出自己的Mod，我们至少需要两样东西：游戏本体和.net framework 4.5，并且建议使用VS2022作为编写代码的软件VS2022与.net framework 4.5的安装

* * *

VS是官方（大崩砖）推荐的编写Mod软件，本文编写时最新版是VS2022

[VS2022官网下载链接](https://visualstudio.microsoft.com/zh-hans/vs/)

在安装VS时会有很多选项，我们编写Mod只需要使用社区版（Community）与.NET 桌面开发即可

![](https://fs49.org/wp-content/uploads/2022/06/vsi.png)

至于.net framework 4.5则需要通过手动下载（下载旧版vs会自带不需要下载）

[.net framework 4.5包下载](https://www.nuget.org/packages/microsoft.netframework.referenceassemblies.net45)

下载以后是`.nupkg`格式的，改名成`.zip`格式后解压

将解压目录下的`\build\.NETFramework`文件夹内的`v4.5`文件夹复制并覆盖到

`C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework` 目录下
