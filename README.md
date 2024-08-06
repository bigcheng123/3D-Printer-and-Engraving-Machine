### Readme English [https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.en.md](https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.en.md)

### 日本語 Japanese [https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.jp.md](https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.jp.md)
------------------------------------------------------------------------------

# 3D打印机 及  CNC雕刻机 运用

#### 一.项目介绍
使用  **3D打印机**  +  **CNC雕刻机**  制作木型，实现产品的形状检查（人工目视）、产品的零部件、标记缺失检查、产品标记颜色检测（传感器检测）的功能

#### 二.项目图片

 **设计图** : 根据产品的图纸、公差等信息，使用solidwork绘制三维模型

![输入图片说明](01_Summary/%E6%9C%A8%E5%9E%8B%E8%AE%BE%E8%AE%A1%E5%9B%BE.jpg)

 **实物图** ：使用3D打印机 + 雕刻机 + 外购标准件 的方式制作实物

![输入图片说明](01_Summary/%E6%9C%A8%E5%9E%8B%E5%AE%9E%E7%89%A9%E5%9B%BE.jpg)

#### 三.3D Printer 介绍

 **1. 型号 ：**   Raise 3DRaise pro3 plus

 **2. 价格 ：**  ￥44999 
 
 **3. 基本参数:** 
  - 打印尺寸：300×300×605mm（单喷头）   255×300×605mm（双喷头）   
  - 机身尺寸:620×626×1105mm
  - 耗材直径：1.75mm
  - 支持材料：PLA/ABS/HIPS/PC/TPU/TPE/PETG/ASA/PP/PVA/尼龙/玻纤增强/碳纤增强/金属填/木质填
  - 层厚：0.01mm~0.25mm
  - 支持格式: .stl / .obj  / .3MF  / .OLTP
  - 详细介绍： https://item.jd.com/100014643451.html#crumb-wrap （京东）
  - 打印机图片：

![输入图片说明](01_Summary/3D%E6%89%93%E5%8D%B0%E6%9C%BA_Raise3D%20PRO3%20PLUS.jpg)


 **4. 使用说明：** 

   使用3D绘图软件，例如solidworks、UG、catia等绘制三维模型并导出.STL格式

   使用切片软件(idea Maker)对.stl文件进行处理，生成3D打印机可以识别的打印程序

   将打印程序上传至3D打印机中，并点击开始打印即可

![输入图片说明](01_Summary/%E6%89%93%E5%8D%B0%E6%9C%BA%E6%93%8D%E4%BD%9C%E6%B5%81%E7%A8%8B.jpg)
    
 **5. 3D打印案例：** 




#### 四.CNC 雕刻机 介绍

 **1. 型号 ：**   3040台式雕刻数控铣床-800W
 
 **2. 价格：**  ￥2900
 
 **3. 基本参数:** 
  - 有效行程：285×410mm    
  - 机身尺寸：500*500mm
  - 支持材料：尼龙 / 电木 / 亚克力 / 木头 / 铝 ......
  - 支持软件: 精雕 / UG / MasterCam / solidworks cam / PowerMill ......
  - 详细介绍： https://item.taobao.com/item.htm?spm=a1z0d.6639537/tb.1997196601.204.6eee7484eKDyp0&id=618733471891&skuId=4533772730407 （淘宝）
  - 雕刻机图片：

![输入图片说明](01_Summary/%E9%9B%95%E5%88%BB%E6%9C%BA.jpg)


 **4. 使用说明:** 

   使用solidworks等三维软件绘制三维模型，并输出 .igs 格式

   将 .igs 格式的文件导入 精雕 软件进行刀路编程，并生成 .NC 程序

   将 NC 程序导入雕刻机控制软件，并进行对刀操作

   开始选择刀路程序并加工零件

   ![输入图片说明](01_Summary/%E9%9B%95%E5%88%BB%E6%9C%BA%E6%93%8D%E4%BD%9C.jpg)
   

 **5. 加工案例:** 

![输入图片说明](01_Summary/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240612175034.jpg)

![输入图片说明](01_Summary/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240612175045.jpg)

![输入图片说明](01_Summary/%E5%9B%BE%E7%89%871.jpg)  ![输入图片说明](01_Summary/%E5%9B%BE%E7%89%872.jpg)  ![输入图片说明](01_Summary/%E5%9B%BE%E7%89%873.jpg) 

#### 五.其他

1.  3D打印软件  **ideaMaker**  地址:  https://www.raise3d.cn/ideamaker-2/   （免费）

2.  CNC雕刻机编程软件  **精雕**  地址: https://surfmill.jingdiaosoft.com/download/User/User/submit   （3轴以下免费）

3.  雕刻机控制软件：购买雕刻机时商家提供控制软件

4.  solidworks软件： 请向正规代理商咨询


#### 声明

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
