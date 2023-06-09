# 第一部分：字符设备驱动基础

这里，我们将介绍什么是设备驱动程序、名称空间、 **Linux 设备模型** ( **LDM** )基础知识以及角色设备驱动程序框架。我们将实现简单的`misc`驱动程序(利用内核的`misc`框架)。我们将建立用户和内核空间之间的通信(通过各种接口，如`debugfs`、`sysfs`、`netlink`插座和`ioctl`)。您将学习如何在外围芯片上使用硬件输入/输出内存，以及理解和处理硬件中断。您还将学习如何使用内核特性，如内核级计时器、创建内核线程和使用工作队列。

本节包括以下章节:

*   [第 1 章](1.html)，*编写简单的杂项字符设备驱动程序*
*   [第二章](2.html)、*用户-内核通信路径*
*   [第 3 章](3.html)，*使用硬件输入/输出存储器*
*   [第 4 章](4.html)，*处理硬件中断*
*   [第 5 章](5.html)、*使用内核定时器、线程和工作队列*