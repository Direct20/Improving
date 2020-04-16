声明(20200417)：
作者目前是一名高中生，爱好编程。此程序作于2019年暑假，暑假结束时发布了1.0.0.1Beta版本，耗时1个月，代码量1.1万行左右。私以为此程序早期框架搭建不够细致，致使后期代码结构混乱。因时间、精力有限，此项目难以继续开发，遂决定开源，愿有缘者与之相见。因时间匆忙，未提供详细程序文档，望谅解。本人水平有限，不足之处望多多包涵。

exe目录下为发布版本
src目录下为源码

源码说明：
C++，Visual Studio 2015，MFC应用程序。
目录：	.vs(VS自动生成)
	Debug(调试输出目录)
	Release(发布输出目录)
	datafiles(题目数据文件)
	bin(配置文件)
	dll(动态链接库)
	res(资源)
	temp(临时目录)
开源引用(.h/.cpp)：zip(zip压缩)
		   unzip(zip解压)
通用(.h/.cpp)：	MemoryDC(绘图处理)
		AnimateBox(动画框)
		DesktopIcon(动画对象)
		DataDef(树状数据结构)
		GlobalFuncs(常用函数库)
窗口类(.h/.cpp)：ImprovingDlg(主窗口)
		 BrowseDlg(浏览窗口)
		 ImgDisplayDlg(图像显示窗口)
		 ImprEditDlg(题目编辑窗口)
数据处理(.h/.cpp)：DataProcess(配置文件读取)
		   Subject(单一题目数据)
		   FileProcess(题目数据文件读取)
其他：	consts.h(常量)
	Exceptions.h(异常处理)
	Subclass(子类化)
	targetver.h
	resource.h
	stdafx
	improving

更多内容参见源码目录下MFC自动生成的ReadMe.txt。