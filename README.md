# OpenMV IDE porting
### 项目名称
基于K210的OpenMV IDE移植

### 支持单位
嘉楠科技

### 项目描述

K210是嘉楠科技推出的一款集成机器视觉与机器听觉能力的系统级芯片(SoC)。它采用RISC-V架构，具有双核64 位处理器，它在芯片中还集成了一个通用神经网络处理器（KPU）， 支持机器视觉和机器听觉多模态识别，可以在公开市场方便的以低成本购买。OpenMV是一个开源、低成本功能强大的机器视觉模块，其项目提供了一个集成化的OpenMV ide集成编程环境， 包括一个功能强大的文本编辑器，一个帧缓冲查看器，直方图显示器，以及一个用于OpenMV调试输出的集成串行终端，在爱好者中拥有广泛的拥趸。由于K210没有OpenMV IDE默认的USB通讯接口， K210无法直接与OpenMV IDE对接使用，但是我们可以通过对K210和OpenMV IDE的改造，通过其它方式进行协议转接移植。


### 所属赛道

2022全国大学生操作系统比赛的“OS功能挑战”赛道


### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生/研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求


### 项目导师
* 张涛： zhangtao##canaan-creative.com
* 黄真明： huangzhenming##canaan-creative.com
### 难度

中等


### 特征

- 基于K210硬件板实现
- 利用既有的SPI, UART, WIFI等通讯接口，实现与OpenMV IDE的对接

### 参考资料
- https://github.com/kendryte/K210-Micropython-OpenMV
- https://github.com/openmv/openmv-ide
- K210 PaddlePi开发板硬件原理图

### License

不限开源协议


## 预期目标

### 说明

要求利用基于K210硬件板相关硬件接口，对OpenMV IDE和K210 SDK进行开发，完成程序编辑、图像预览、直方图显示，软件调试等功能即为完成。
参赛者完成题目，考虑调试和预览性能、易用性、成本等综合评分。