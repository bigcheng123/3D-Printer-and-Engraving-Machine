### Readme English [https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.en.md](https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.en.md)

### 日本語 Japanese [https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.jp.md](https://gitee.com/trgtokai/3ddayinjicncdiao/blob/master/README.jp.md)
------------------------------------------------------------------------------

# 3DプリンターおよびCNC彫刻機の利用

#### 一. プロジェクト紹介
**3Dプリンター**と**CNC彫刻機**を使用して木型を製作し、製品の形状検査（目視）、製品部品の欠損検査、製品のマーク色検査（センサー検出）の機能を実現します。

#### 二. プロジェクト画像

**設計図** : 製品の図面、許容範囲などの情報に基づき、SolidWorksを使用して三次元モデルを作成します。

![输入图片说明](01_Summary/%E6%9C%A8%E5%9E%8B%E8%AE%BE%E8%AE%A1%E5%9B%BE.jpg) 

**実物図** ：3Dプリンターと彫刻機、および外部調達の標準部品を使用して実物を製作します。

![输入图片说明](01_Summary/%E6%9C%A8%E5%9E%8B%E5%AE%9E%E7%89%A9%E5%9B%BE.jpg)

#### 三. 3Dプリンターの紹介

**1. 型号 ：** Raise 3D Raise pro3 plus

**2. 価格 ：** ￥44999 

**3. 基本パラメーター:** 
- 印刷サイズ：300×300×605mm（シングルヘッド）、255×300×605mm（デュアルヘッド）
- 本体サイズ：620×626×1105mm
- 材料直径：1.75mm
- 対応材料：PLA/ABS/HIPS/PC/TPU/TPE/PETG/ASA/PP/PVA/ナイロン/ガラス繊維強化/カーボン繊維強化/金属充填/木質充填
- 層厚：0.01mm~0.25mm
- 対応フォーマット: .stl / .obj  / .3MF  / .OLTP
- 詳細紹介： https://item.jd.com/100014643451.html#crumb-wrap （京東）
- プリンター画像：

![输入图片说明](01_Summary/3D%E6%89%93%E5%8D%B0%E6%9C%BA_Raise3D%20PRO3%20PLUS.jpg)

**4. 使用方法：** 
- SolidWorks、UG、CATIAなどの3D CADソフトを使用して三次元モデルを作成し、.STL形式でエクスポートします。
- スライスソフト（IdeaMaker）を使用して.STLファイルを処理し、3Dプリンターが認識できる印刷プログラムを生成します。
- 印刷プログラムを3Dプリンターにアップロードし、印刷を開始します。

![输入图片说明](01_Summary/%E6%89%93%E5%8D%B0%E6%9C%BA%E6%93%8D%E4%BD%9C%E6%B5%81%E7%A8%8B.jpg)
    
**5. 3Dプリントの事例：** 

![输入图片说明](01_Summary/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240612175034.jpg)

![输入图片说明](01_Summary/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20240612175045.jpg)

#### 四. CNC彫刻機の紹介

**1. 型号 ：** 3040デスクトップ彫刻数控フライス盤-800W
 
**2. 価格：** ￥2900
 
**3. 基本パラメーター:** 
- 有効ストローク：285×410mm    
- 本体サイズ：500×500mm
- 対応材料：ナイロン / 電木 / アクリル / 木材 / アルミニウム ......
- 対応ソフトウェア: 精雕 / UG / MasterCam / SolidWorks CAM / PowerMill ......
- 詳細紹介： https://item.taobao.com/item.htm?spm=a1z0d.6639537/tb.1997196601.204.6eee7484eKDyp0&id=618733471891&skuId=4533772730407 （淘宝）
- 彫刻機の画像：

![输入图片说明](01_Summary/%E9%9B%95%E5%88%BB%E6%9C%BA.jpg)

**4. 使用方法:** 
- SolidWorksなどの3D CADソフトを使用して三次元モデルを作成し、.IGS形式でエクスポートします。
- .IGS形式のファイルを精雕ソフトにインポートし、ツールパスをプログラムして.NCプログラムを生成します。
- NCプログラムを彫刻機のコントロールソフトにアップロードし、対刀操作を行います。
- ツールパスプログラムを選択して部品の加工を開始します。

![输入图片说明](01_Summary/%E9%9B%95%E5%88%BB%E6%9C%BA%E6%93%8D%E4%BD%9C.jpg)

**5. 加工事例:** 

![输入图片说明](01_Summary/%E5%9B%BE%E7%89%871.jpg)
![输入图片说明](01_Summary/%E5%9B%BE%E7%89%872.jpg)
![输入图片说明](01_Summary/%E5%9B%BE%E7%89%873.jpg)


#### 五. その他

1.  3Dプリンターソフト **ideaMaker** のダウンロード先:  https://www.raise3d.cn/ideamaker-2/   （無料）

2.  CNC彫刻機のプログラミングソフト **精雕** のダウンロード先: https://surfmill.jingdiaosoft.com/download/User/User/submit   （3軸以下無料）

3.  彫刻機のコントロールソフト：購入時に販売店から提供されるコントロールソフト

4.  SolidWorksソフト：正規代理店にお問い合わせください

#### 声明

1.  Readme\_XXX.md を使用して異なる言語をサポートします。例: Readme\_en.md, Readme\_zh.md
2.  Gitee公式ブログ [blog.gitee.com](https://blog.gitee.com)
3.  Giteeの優れたオープンソースプロジェクトについては、[https://gitee.com/explore](https://gitee.com/explore) をご覧ください。
4.  [GVP](https://gitee.com/gvp) は、Gitee最有価値オープンソースプロジェクトの略称で、総合評価に基づいた優れたオープンソースプロジェクトです。
5.  Gitee公式の使用マニュアルは [https://gitee.com/help](https://gitee.com/help) をご覧ください。
6.  Giteeスターズ