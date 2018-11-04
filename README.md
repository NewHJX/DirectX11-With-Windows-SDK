# DirectX11 With Windows SDK系列教程与演示项目

## 基本配置
IDE：Visual Studio 2017 Community

语言：C++/HLSL

目前项目不依赖第三方库，但从微软官方项目中提取了下述模块到项目中：</br>
[DirectXTex/DDSTextureLoader](https://github.com/Microsoft/DirectXTex/tree/master/DDSTextureLoader)</br>
[DirectXTex/WICTextureLoader](https://github.com/Microsoft/DirectXTex/tree/master/WICTextureLoader)</br>
[DXTK/Mouse(源码上有所修改)](https://github.com/Microsoft/DirectXTK/tree/master/Src)</br>
[DXTK/Keyboard(源码上有所修改)](https://github.com/Microsoft/DirectXTK/tree/master/Src)</br>
[DXUT/dxerr](https://github.com/Microsoft/DXUT/tree/master/Core)</br>


Windows SDK版本：默认**10.0.17134.0**，理论上目前可以支持Windows 10 SDK的任何版本

平台: 支持x86/x64, 可Debug/Release模式


## 注意事项
该项目作为教程演示项目，并不是以实现一个软引擎为目标，因此不会刻意进行引擎架构的组织。建议读者在跟随教程学习的同时要动手实践。

**在删去DXTK库后，现在的任何一个项目都可以独自生成、运行了。**

## 如何打开教程项目
如果是从解决方案(.sln)打开的话，若要指定哪个项目，需要对项目右键-设为启动项。

![](https://github.com/MKXJun/DirectX11-With-Windows-SDK/blob/master/MarkdownFiles/001.jpg)

然后对项目右键-选择生成，或者对整个解决方案进行生成都可以。

![](https://github.com/MKXJun/DirectX11-With-Windows-SDK/blob/master/MarkdownFiles/002.jpg)

## 博客教程

目前对应的博客更新：

[博客园](https://www.cnblogs.com/X-Jun/p/9028764.html)（优先保证最新）

[CSDN](https://blog.csdn.net/x_jun96/article/details/80293670)

## QQ群交流

QQ群号：727623616

欢迎大家来交流，以及项目有什么问题也可以在这里提出。


## 更新记录

该项目的更新记录位于Updates.md

