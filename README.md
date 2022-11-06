# Ros_Learning
Ros学习的历程

## 第一周视频学习至 p.56
一开始，粗略的了解了ros的相关概念及其作用，然后在ubuntu20.04系统下比较顺利的完成安装noetic版本及其相关配置。

然后了解了launch文件的使用，自己的理解就是launch相当于一个脚本的作用，当运行launch文件时，可以一次执行多个任务节点，能够简便我们的操作。

之后学习了关于ROS的架构：

ROS文件系统主要如下：

![文件系统](./README.assets/文件系统.jpg)

根据该文件系统的框架，学习了如何创建功能包、src目录下cpp文件的编写、scripts目录下python文件的编写并且程序编译时需要配置的CMakeLists.txt以及package.xml文件以及在ros中常用的命令。

最后，了解了ROS的三种基本通信方式，目前学习到话题通信，根据ros自带的一些功能函数，实现了订阅方和发布方之间的通信。


## 第二周视频学习至p.96
本周主要学习了ROS通信中的三种机制中的服务通信和参数服务器，了解了其中每种通信机制是如何工作的，以及熟悉并操作其相关实现。
其次学习了ros中一些比较常用的命令来查看通讯时相关的信息。


## 第三周视频学习至p.142
本周主要学习了ros中常用的一些API，主要学习内容还是与上周通信相关的一些API以及时间、日志输出相关API，主要详细的了解并使用了这些函数的使用方法。