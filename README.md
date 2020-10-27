# MelonLoader-YuanShen
Modified version of Melonloader that allows you to load your custom mod into the game YuanShen(原神)
 
一个修改版的MelonLoader，可将你自定义的mod加载进原神（PC版）

## Usage

Put everything into game folder of YuanShen, and launch game directly, you should see main window of a mod called Explorer.

将所有文件放到原神根目录然后直接启动游戏，一个叫Explorer的mod应该直接显示。

## Notice

You will not be able to login in the game with this mod, bypass the mhyprot2,the CRC of UserAssembly.dll, and the file check is required to be able to login in the game with this mod installed. ~~Source code is not included at this time, I will release it after this loadder became invalid.~~ Source code is now available.

You will also need modified version of Il2CppAssemblyUnhollower in order to analysis UserAssembly.dll and create runtime files, see [Il2CppAssemblyUnhollower-YuanShen](https://github.com/kagurazakasanae/Il2CppAssemblyUnhollower-YuanShen)

使用此mod你将无法登录进入游戏，带着此mod登录进入游戏需要绕过mhyprot2，UserAssembly.dll的代码CRC以及绕过游戏对游戏目录的文件检查。~~目前不开放源码，需要看什么自己dnspy看，源码将会在该mod失效之后放出。~~ 源码已经公开。

该项目同时依赖修改过后的Il2CppAssemblyUnhollower来分析UserAssembly.dll并生成对应的依赖库，请参见[Il2CppAssemblyUnhollower-YuanShen](https://github.com/kagurazakasanae/Il2CppAssemblyUnhollower-YuanShen)



## Demo

![demo](https://raw.githubusercontent.com/kagurazakasanae/MelonLoader-YuanShen/main/111.png)
