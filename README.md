# 三角波发生器
### 实现功能
简易的可改变幅值与频率的三角波发生器，三角波会在示波器上显示。</br>
本项目主要使用8086，8255A与0832三个芯片。
### 使用方法
运行仿真后，弹出示波器，稍等一下，波形将会显示，通过改变8255A芯片的PA或PB口所连接的开关，波形将会发生改变。开始默认幅值为5，增幅为01H</br>
PA口控制的是幅值，PB口控制的是频率。</br>
PA口开关在此程序下，改变幅值为1~5，闭合开关1，幅值为1；闭合开关1和2，幅值为2，依次类推，其他任何情况的幅值都为5。</br>
PB口开关在此程序下，改变的增幅为01H和03H，闭合增加开关，断开减少开关，增幅将改变为03H；断开增加开关，闭合减少开关，增幅将改变为01H。
### 使用软件及其编译环境
使用软件为 Proteus 8.9 professional</br>
编译器为 [MASM32](http://www.masm32.com/)
### 演示
演示地址: [https://www.bilibili.com/video/BV1s64y1X7aM/](https://www.bilibili.com/video/BV1s64y1X7aM/)