# Awesome-TFmini

TFmini信息收集.  [English Version Readme](/README.md)  

- [Official](#official)   
- [Examples](#examples)  
- [Applications](#applications)  



## Official
- [TFmini主页](http://benewake.com/tfmini.html)   
- [官方资料](http://benewake.com/down.html)  
- [淘宝购买链接](https://item.taobao.com/item.htm?spm=a1z10.3-c.w4002-15511889465.14.58ac1084x6ubC&id=554821569293), 可直接联系[北醒](http://benewake.com/index.html)  



## Examples

- [TFmini-Arduino](https://github.com/TFmini/TFmini-Arduino)
<br>给出了TFmini在Arduino上的几个例子: 硬件串口轮询, 硬件串口中断, 模拟串口, 模拟串口连接多个TFmini, 模拟串口测频率, I2C一主一从等.  

- [TFmini-RaspberryPi](https://github.com/TFmini/TFmini-RaspberryPi)
<br>给出了TFmini在树莓派3上的例子: 硬件串口, 模拟串口, 用Python2或者Python3实现, 代码可以在macOS, Linux, Windows等系统上使用.   

- [TFmini-Pyboard](https://github.com/TFmini/TFmini-Pyboard)
<br>TFmini在Pyboard上的例子, 用 MicroPython 编程实现. 

- [TFmini-STM32](https://github.com/TFmini/TFmini-STM32)
<br>TFmini的STM32例程, 使用STM32CubeMX、Keil作为开发工具, 包含2种TFmini通讯协议，分别为：PIX、Standard Data Format(89BYTE)). 包含3种转换方式：开关量、CAN、IIC. 

- [TFmini-51MCU](https://github.com/TFmini/TFmini-51MCU)
<br>TFmini在51单片机说上面的例程, 如STC89C59, STC12C5A60S2, STC15W204S, STC15F2K60S2等, 使用了硬件串口或者模拟串口. 

- [TFmini-Processing](https://github.com/TFmini/TFmini-Processing)
<br>TFmini的Processing例程, 包含控制台和GUI两个例子, 代码可以在macOS, Linux, Windows等系统上使用. GUI如下: 
<br>
<br> ![tfminiGUI](https://github.com/TFmini/TFmini-Processing/raw/master/Assets/tfminiGUI.png)  

- [TFmini-macOS](https://github.com/TFmini/TFmini-macOS)
<br>用 USB转串口(CH340, CP210x等) 连接 TFmini 到 MacBook 上. 使用 Xcode 9 & Swift 4 & ORSSerialPort库 开发.  可以直接在 [release](https://github.com/TFmini/TFmini-macOS/releases) 下载 TFmini-1.0.dmg 安装使用.
<br>
<br> ![](https://github.com/TFmini/TFmini-macOS/raw/master/Assets/TFminiGUI.jpg)  

---

- [patrickpoirier51/TFMINI](https://github.com/patrickpoirier51/TFMINI)
<br>TFmini Arduino驱动. 

- [patrickpoirier51/TFMINI_MAXBOTIX_EMULATOR](https://github.com/patrickpoirier51/TFMINI_MAXBOTIX_EMULATOR)
<br>仿效超声波传感器, TFmini通过Arduino转成I2C连接到飞控上. 

- **[opensensinglab/tfmini](https://github.com/opensensinglab/tfmini)**
<br>TFmini 的 Arduino 驱动, 可以直接在Arduino IDE的库中搜索到.    

- [MomsFriendlyRobotCompany/tfmini](https://github.com/MomsFriendlyRobotCompany/tfmini)  
<br>TFmini 的 Python 驱动. 




# Applications 

客户使用TFmini案例汇总

- [TFmini通过I2C接口在Pixhawk的操作使使用案例](https://discuss.ardupilot.org/t/how-to-make-the-tfmini-rangefinder-talk-i2c/24403)
<br>本案例详细介绍了通过I2C通讯协议在pixhawk飞控使用说明其中包含：I2C接口程序、TFmini在Pixhawk演示视频。

- [TFmini通过I2C接口多个TFmini在Pixhawk避障的操作使用案例](https://discuss.ardupilot.org/t/avoidance-experiments-with-the-poc-and-benewake-tfmini/25277)
<br>本案例详细介绍了通过I2C接口多个TFmini同时工作在pixhawk飞控避障使用说明其中包含：I2C接口程序、多个TFmini在Pixhawk同时工作的演示视频。

- [TFmini在Teensy3.5转接板操作使用案例](https://discuss.ardupilot.org/t/benewake-tfmini-inexpensive-lidar-with-teensy-3-5/24510)
<br>本案例详细介绍了TFmini在Teensy3.5转接板的操作流程，包含线序的连接、数据的读取。
 
- [patrickpoirier51/TFMINI-POC](https://github.com/patrickpoirier51/TFMINI-POC)
<br>使用TFmini做的无人机避障系统.   


