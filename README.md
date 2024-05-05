# icon-convertor
图标转换助手（图形界面），svg、png转icns、ico、png，只需鼠标点点点即可～

## 背景
在开发跨平台桌面应用时，存在图标转换到对应平台格式的需求，如：
- linux图标为png格式；
- macos图标为icns格式，底层包含多种尺寸的图像；
- windows图标为ico格式，底层包含多种尺寸的图像；

然而，没有一款功能完善、好用且免费的图标转换软件，故开发了本软件。

## 现状
现状，现有的一些图标在线转换的工具也存在着一些问题：
- 转换的质量较差，在打包进应用后效果非常差；
- 甚至有时转换后的icns、ico图像尺寸缺失，导致打包进应用后图标不显示；
- 功能单一，有的只支持svg转png、png转icns，功能不全面。

## 特点
- 支持svg、png图像转Icns，支持全规格icns（ic7，ic8，ic9，ic10，ic11，ic12，ic13，ic14），mac应用打包时不再担心图标不生效问题；
- 支持svg、png图像转Ico，可选多种尺寸的图像；
- 支持非标svg图像，现有的svg图像库在处理非标svg图像时可能导致颜色丢失（全黑）和颜色不正常（偏紫色）的情况，本软件采用浏览器渲染的方式完美绕过了颜色丢失的问题；
- 完全免费。

## 界面
> 在release页面点击下载对应平台的软件。

![preview](https://github.com/MarsSwimmer/icon-convertor/assets/146618222/ccc0805f-1683-4a31-bd87-1bb7afd7b824)

![detail](https://github.com/MarsSwimmer/icon-convertor/assets/146618222/53e12827-9586-4202-b129-9499fdf6216f)

![result](https://github.com/MarsSwimmer/icon-convertor/assets/146618222/520f1e7f-8cf5-4150-ae0a-a6738b8b8add)
