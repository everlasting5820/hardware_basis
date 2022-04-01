## 手册寻找方法：
     1.官网手册
     2.www.alldatasheet.com
     3.浏览器



## 画原理图封装步骤
### 1.建立工程
### 2.对应引脚 (包括颜色，大小，长短，电气属性)  尤其要注意引脚序号和引脚名
    note：  ad中引脚的四个点朝外
### 3.保存元件的属性和原件的名字
### 4.遇到多引脚的元件，可以拆分成多个原理图

## 画pcb封装步骤
      封装和器件有可能不是一一对应关系，可以一个对多个
### 1.建立工程
     note：一般情况按手册中推荐的封装图进行绘制 example board loyout 

![1648801979462](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648801979462.png)

    note: 前为毫米后为英尺。一般按最大范围去画
### 2.画一个焊盘。中心绿色为通孔 焊盘属于顶层（top layer 覆铜层红色）
    bottom layer 底层 
    mechanical 机械层
    keepout layer 禁止布线层
    top overlay 顶层丝印层   （白线一般作为注释和轮廓线）
    bottom overlay 底层丝印层
    top paste 顶层助焊层
    bottom paste 底层助焊层
    top solder 顶层阻焊层
    bottom soldr  底层阻焊层
    drill guide  过孔引导层
    drill drawing  过孔钻孔层
    multilayer 多层
### 3.改变焊盘形状尺寸， 按照间距规则来调整。
    按Q可以实现毫米到mil转换
### 4.设定其中一个为坐标参考标号排列即可。可以设置对相应的对其方式
	可以在右下角设置捕捉方式
### 5.画轮廓（top overlay）。一般选取最大值，留有一定的余量。
	可以使用快捷键测量确定
	标注1角可以便于观察，便于分辨
	按手册上，pcb的封装与原理图的封装要完全对应
	一般情况需要校对，简单但关系到整个电路板的成败
	






















    常见贴片元件及其封装
![1648803334621](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648803334621.png)
    
![1648803460235](C:\Users\71801\AppData\Roaming\Typora\typora-user-images\1648803460235.png)

