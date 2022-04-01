## 原理图功能分类
### 1.控制部分
	整个电路板的核心控制和计算部分
	控制器分类：
	CPU：顺序执行 MCU，DSP，GPU，NPU等等
	FPGA：并行执行 FPGA，CPLD
### 2.接口部分
	实现特定功能的部分
	（io检测，rs232，rs485）
	boot确定启动模式


![1648814957785](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648814957785.png)



### 	3.电源部分

	整个电路板的供电部分

* 最小系统板包含电源晶振复位
* ![1648814896105](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648814896105.png)

## stm32为例，要关注的主要信息
	内核 m3
	主频  运行速度
	memories    flash相当于手机储存，SRAM相当于手机内存
	时钟信息 晶振 内部外部，外部比内部准，外部先启动  RTC做实时时钟
	电源  复位方式  低功耗模式
	DMA  不经过核传输数据
	I/O口 高电平和低电平
	debug 仿真 swd和jtag
	timer定时器
	串口  spi iic
	选型表 资源介绍，引脚

​	资源配置表![](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648814749251.png)
​	

时钟树

![1648814826573](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648814826573.png)