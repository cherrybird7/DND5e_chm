# DND5e不全书
这里是5e不全书，即《龙与地下城》五版资源中文整合项目，并非《5e全书》，也不会以任何人的名字署名。

本项目的产物——CHM文件在Windows环境下可以直接打开，如果您是手机或非Windows系统的电脑需要特殊的文件查看器来打开。如果您是贡献者，您可能还需要python与html有关的开发环境。

本项目主要的使用工具为
[优秀小巧的 CHM 编辑器 WinCHM Pro 5.492 中文免费版 - 大眼仔旭 (dayanzai.me)](http://www.dayanzai.me/winchm.html)

## 如何向本项目作出贡献？

您可以选择三种身份，其一是需要高频更改内容的贡献者，其二是中频维护内容的贡献者，其三是检查到文本有错误的纠错者。前两种身份需要Github账户与特殊上网方式，而每次修订者的贡献都会被git系统所记录。

如果您是纠错者，请提交[点击此链接](https://docs.qq.com/form/page/DRVV3WFFvbGJmcEVp#/fill)提交纠错表，且可以在[纠错表查询](https://docs.qq.com/sheet/DRWdXb0lQbXVlcFBH)查看到修改回馈。

如果您是需要超高频更改内容的贡献者，您需要一个Github账户，且需要掌握Github的基础操作，并联系星尘将您的账户加入Push权限列表。

如果您是中频维护内容的贡献者（推荐），您同样需要一个Github账户，并使用pull requests功能发起合并请求，经检查后会合并入主分支。

不全书维护使用的软件为**WinCHM Pro 5.528 中文免费版**，您可以在[这里](http://www.dayanzai.me/winchm.html)获取；推荐Github客户端为**GitHub Desktop**，您可以在[这里](https://desktop.github.com/download/)下载；额外的不全书页面制作与排版工具为果园拟像术，您可以在[这里](https://github.com/DND5eChm/Python_Simulacrum/releases)取得。注意，这种贡献方式只能使用WIN系统。

下列两个视频将演示第二种贡献方式，它涵盖了第一种贡献方式的步骤。

*教学视频：*[星尘录的](https://www.bilibili.com/video/BV1H4421U7mZ/),[咸喵录的](https://www.bilibili.com/video/BV1mE4m1R79W/)

如果您对此有任何问题或希望做出贡献也可以通过QQ联系咸喵（2240146845）

## 注意事项

**根目录中的`.wcp`文件为工程文件，如果您不是第一种贡献者，请不要pull requests 不全书.wcp 的修改，这并不会被合并，因为它是一个特殊格式文件。**

**所有的html与htm文件应该是GBK编码(或强行使用GB2312编码)，所有的WCP文件应该是UTF16-LE编码。**

**文件夹`...\DND5e_chm\Generator`中的所有python文件都需要使用同文件夹下的`run.bat`进行运行，否则极大概率出现问题，这些python文件都是起到便捷辅助作用的。**

如果您有更新目录的需求，您可以创建一个新的wcp文件，如根目录下的其他wcp文件一样，与修改或新增的html文件一同添加至pr流程进行合并，仓库协作者会手动将其合入主wcp文件中。
