![](docs/images/icon.png)

# Loxodon Framework XLua

[![license](https://img.shields.io/badge/license-MIT-blue.png)](https://github.com/cocowolf/loxodon-framework-xlua/blob/master/LICENSE)
[![release](https://img.shields.io/badge/release-v1.1.0-blue.png)](https://github.com/cocowolf/loxodon-framework-xlua/releases)


**要求Unity 5.6.0或者更高版本**

Loxodon.Framework框架的XLua插件，它是一个lua的MVVM框架，支持lua和c#混合编程或者也可以完全使用lua来编写您的整个游戏。

## Quick start ##


1. You can download the latest version of xlua from Xlua's Github repository,the file name is usually xlua_v2.x.xx.zip, unzip and copy it to your project.(XLua Download:https://github.com/Tencent/xLua/releases)

2. Configure a macro definition called "XLUA" in PlayerSetting/Scripting Defin Symbols.It is recommended to configure all platforms.

3. Find Loxodon.Framework.XLua.unitypackage in the LoxodonFramework/Docs/XLua directory and import it into the project.

4. Please see the example in the LoxodonFramework/Lua/Examples directory to enjoy your lua tour.


## 导入教程 ##


1. 从Xlua的Github仓库下载最新版的XLua，可以使用源码版本Source code.zip或者xlua_v2.x.xx.zip版本（建议使用xlua_v2.x.xx.zip版本，避免命XLua目录下测试类导致的类名冲突）。将下载好的xlua解压缩，拷贝到项目中。

2. 配置Unity3D项目PlayerSetting/Scripting Defin Symbols，添加XLUA的宏定义，为避免出错，最好将PC、Android、iOS等平台的都配上。

3. 导入LoxodonFramework目录下Docs/XLua/Loxodon.Framework.XLua.unitypackage。如果出现编译错误，请检查是否导入了XLua的Examples目录，这个目录下的InvokeLua.cs文件定义了PropertyChangedEventArgs类，因没有使用命名空间，会导致和System.ComponentModel.PropertyChangedEventArgs类冲突，请删除XLua目录下的Examples文件夹或者给InvokeLua.cs文件中的PropertyChangedEventArgs类添加上命名空间。

4. 打开LoxodonFramework/Lua/Examples 目录，查看示例。

## 联系方式
邮箱: [yangpc.china@gmail.com](mailto:yangpc.china@gmail.com)   
网站: [https://cocowolf.github.io/loxodon-framework/](https://cocowolf.github.io/loxodon-framework/)  
QQ群: 622321589 [![](https://pub.idqqimg.com/wpa/images/group.png)](https:////shang.qq.com/wpa/qunwpa?idkey=71c1e43c24900ee84aeffc76fb67c0bacddc3f62a516fe80eae6b9521f872c59)