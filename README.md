# vfive-board
    
    这是一块基于RISC-V架构的国产芯片全志D1设计开发的一块以网络通讯为主要场景的开发板。

## vfive的由来
          
    随着CISC架构越来越复杂，专利累加越来越多，工艺难度也越来越大，后进者想进入这个领域
也越来越困难。
    2010年伯克利研究团队提出的RISC-V让我们看到一种更开放的和更有发展潜力的硬件指令集体
系结构，作为物联网、网络通讯和人工智能相关领域的多年从业者，我们通过RISC-V看到了新的产
业希望，为此我们基于RISC-V架构的国产芯片全志D1设计开发了一块以网络通讯为主要场景的开发
板openV D100，并将OpenWRT移植到了RISC-V架构。

## 电路板概念图
![](http://www.openv.cc/wp-content/uploads/2022/03/1010889489-1024x708.jpg)

## 电路板特性
 * CPU	全志D1-H C906 RISC-V
 * RAM	DDR3 512MB
 * FLASH	支持TF卡作为启动盘，预留SPI扩展
 * 以太网通信	支持VLAN的5网口千兆以太网(2个接口3个排针)
 * 无线通信	板载WIFI与蓝牙模块，支持softAP模式
 * 工业总线	RS485*1
 * 显示	支持HDMI输出，支持SPI输出
 * 音频	支持3.5mm的音频输入输出接口
 * 按键	GPIO按键*1
 * LED灯	供电*1，GPIO控制*1
 * DEBUG	支持TTL串口调试，支持ADB USB调试
 * USB	USB HOST*1，USB UTG*1，USB 2.0协议
 * 80pin排针	含一个USB，3个千兆网口，SPI，ADDA和GPIO
 * 电源输入	Type-C USB 5V/2A
 * 板身大小	90*60mm
 * PCB工艺与层数	6层板
 * 操作系统	OpenV官方提供支持OpenWrt路由系统;支持Debian系统

## 电路板进度
    
    目前原理图和PCB设计已经完成，正在样板调试阶段。

## 应用场景建议
 * 企业和家用NAS存储
 * SDN和SD-WAN
 * 智能路由器
 * 工业物联网和AIOT
 * 智能化办公
 * 微型服务器等
