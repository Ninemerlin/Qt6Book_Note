# Welcome
## Structure
学习QML，阅读至5-7章。
有任何想要深入探究的，阅读6-14章。
剩余为高级部分——不在关注QML，但是是构建完整QML程序需要知道的。建议阅读。

# Qt and Qt Quick
嵌入式和联网设备市场，软件功能简单但需要精良且顺滑的用户界面。

## Qt Building Blocks
一些库在Qt支持的的平台上被强制要求存在，形成了Qt Essentials Modules。[或可参考](https://doc.qt.io/qt-6/qtmodules.html)
可选的库构成了Qt Add-On Modules。普通开发者用不上，但是它们确实对一些问题提供了极有价值的解决方案。

注意：一些特殊用途的库也属于Add-On，即使它们能够在所有支持的平台运行

### Core-Essential Modules
令人在意的是，书中“开始QML编程的最小Qt6模块集”只比[在线链接](https://doc.qt.io/qt-6/qtmodules.html)缺少了一个Essential模块：[Qt Quick Dialogs](https://doc.qt.io/qt-6/qtquickdialogs-index.html)

这张图才是精髓。
![[Pasted image 20240604225354.png]]

### Add-On Modules
令人在意的是Qt SQL和Qt XML


## Qt 6 Introduction


# Qt 6 Introduction



# 附录A
## 1 声明式编程
声明式编程是一种编程范式。
开发者只需描述他们想要达到的最终状态或结果，而不是详细说明如何一步步达到那个状态。

在UI开发中，这意味着开发者定义UI组件的结构和外观，以及它们应该如何响应数据变化，而不是具体控制每个组件何时及如何更新。

## 2 反应式编程
反应式编程是一种强调数据流和变化传播的编程范式。
在反应式系统中，当数据发生变化时，系统会自动传播这些变化，影响所有依赖于该数据的部分。

在UI开发领域，这意味着界面能够自动响应数据模型的任何变更，即时更新视图，而无需开发者手动管理这些更新。

## 3 UX designer
用户体验设计师。

「用户体验设计师」的职责：
1，负责包括产品的概念原型设计及细化的交互设计，配合进行用户测试及分析；
2，团队成员合作，交流各种想法，画出原型，参与产品整个的周期；
3，从产品的可用、易用性角度出发，在整个产品生命周期提供可持续性的用户体验设计并跟踪执行。

## 4 D-BUS
[入门参考博客和博主](https://blog.51cto.com/quantfabric/2118184)
D-Bus是Desktop Bus的缩写，是针对桌面环境优化的IPC(InterProcess Communication)机制，用于进程间的通信或进程与内核的通信。

- [ ] IPC


# 附录B
## 1
QtQuick 2.x 随 Qt 5.0 一起引入。
Qt 5.0已经拥有声明式编写页面的能力。