# Connect_App_V4.2_Android二查

|              版本               |      日期      |
| :-----------------------------: | :------------: |
| FX Connect_debug_1.0.4(003).apk | 2020年09月01日 |

| 后缀内容 | 作用               |
| :------- | :----------------- |
| null     | 未修改             |
| 1        | 已修改待复查       |
| 2        | 无法实现待变更讨论 |
| 3        | 已修改未达标       |



### 4.2.2.8 - 首页与资产详情

##### 首页 01

主金额符号与数值相隔应无空格<金额规范法币无空格，数字货币一位空格>**<全局影响>** 3

涨跌三角图标不对 3

###### 涨跌暂无正负值需求 2

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901175225368.png" alt="image-20200901175225368" style="zoom: 33%;" />



##### 首页 012 滚动动效

字号不对

字重不对

左边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901181144237.png" alt="image-20200901181144237" style="zoom:33%;" />



##### 首页 02

状态栏颜色声明未实现 3

###### 弹窗两端动效不一致待确认 2

弹窗样式不完整<边框；阴影>**<全局影响>**   3

项目内容上下边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901182135674.png" alt="image-20200901182135674" style="zoom:33%;" />




##### 添加资产 01

###### 标题栏高度不对   （系统默认高度  不建议修改）2

主副标行距不对

币种图标容器不对<大小；填充；阴影>   3

已添加状态遮罩颜色实现不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901182416888.png" alt="image-20200901182416888" style="zoom:33%;" />



##### 添加资产 011 滚动动效

标题动效有bug<副标题居左至居中闪现位移>   3



##### 添加资产 02

结果卡片底部圆角未实现 3



##### 添加资产 03

币种图标容器行距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901182807634.png" alt="image-20200901182807634" style="zoom:33%;" />

##### 资产详情 01

主金额规范不对   3

币种图标容器左右边距不对    3

地址项区域下边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901183116636.png" alt="image-20200901183116636" style="zoom:33%;" />



##### 资产详情 02

CMC缺失未实现



##### 资产详情 04

地址项拖拽样式不对  3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901183806815.png" alt="image-20200901183806815" style="zoom:33%;" />



##### 通用地址选择 041

全高弹窗高度不对 **<全局影响>**

已添加项目灰度不对      3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901183848195.png" alt="image-20200901183848195" style="zoom:33%;" />



##### 通用地址选择 0421

设置标签UI未更新   3




##### 资产详情 05

项目内容上下边距不对  3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901184033661.png" alt="image-20200901184033661" style="zoom:33%;" />



##### 资产详情 06

该弹窗属无关闭规范  3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901184140842.png" alt="image-20200901184140842" style="zoom:33%;" />



##### 资产详情 071

背景遮罩未实现   3

按钮容器不对<圆角矩形 12dp/pt>  3

主副标行距不对

项目区上边距不对  3

Toast样式不对**<全局影响>**

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200901184457065.png" alt="image-20200901184457065" style="zoom:33%;" />



### 4.2.5.2 - 通知中心 <无法展现 单独查>

##### 通知中心 01 多位

多层通知未展现 待查

通知角标样式不对<无阴影，有描边>    11111

通知内容上边距不对   1111



##### 通知中心 02

标题栏高度不对   11111

"Fold"字重不对   11111

通知卡片样式不对<边框；阴影>  

时间戳未实现

左滑删除未实现   1111111

背景模糊未实现

多项通知状态未展现 待查



##### 通知中心 031 应用内

应用内通知未展现 待查



### 4.2.7.3 - 转出

##### 发送 01 法币

主金额切换功能闪退 3

法币换算值显示逻辑不对<无键入隐藏，输入内容后显示>

币种图标容器左右边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902100947822.png" alt="image-20200902100947822" style="zoom:33%;" />



##### 发送 02 切换资产

关闭按钮位置不对

主标题下边距不对 

推荐卡片未展现 待查

卡片内项目上下边距不对   3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902101156250.png" alt="image-20200902101156250" style="zoom:33%;" />



##### 发送 021 切换资产滚动

标题栏背景未降级处理

标题栏图标容器未实现

最后一行卡片下边距不对  3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902101400182.png" alt="image-20200902101400182" style="zoom:33%;" />



##### 发送 031 无效输入

主金额动效缺失

主金额输入规则不对<前12后18科学计数/金额动态逻辑：边距极小8pt→字号极小20pt→两折行垂直居中>   3

余额不足文字垂直未居中

换算结果上边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902102054436.png" alt="image-20200902102054436" style="zoom:33%;" />



##### 发送 05 设置手续费

项目行高不对   3

一级按钮字重不对<Medium;18pt/dp>   3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902102210442.png" alt="image-20200902102210442" style="zoom:33%;" />



##### 发送 051 设置手续费超限ETH

状态未复现 待查



##### 发送 06 选择接收人

一级按钮禁用态样式不对   3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902102354571.png" alt="image-20200902102354571" style="zoom:33%;" />



##### 发送 062 选择接收人联想

联想内容行高不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902102510396.png" alt="image-20200902102510396" style="zoom:33%;" />



##### 发送 072 接收人报错

功能未实现



##### 通用支付 01

项目行高不对   3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902102834365.png" alt="image-20200902102834365" style="zoom:33%;" />



##### 通用支付 011

未展现 待查



##### 通用支付 02 并存生物优先

键盘未拉起  3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902103135107.png" alt="image-20200902103135107" style="zoom:33%;" />



##### 通用支付 06 结果

项目内容右边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902103338300.png" alt="image-20200902103338300" style="zoom:33%;" />



### 4.2.9.1 - 转入

##### 首页转入 03

###### 标题栏高度不对  (系统默认) 2



##### 首页转入 032 滚动动效

锚点滚动后未触发阴影  2

标题栏背景未降级处理  3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902103914796.png" alt="image-20200902103914796" style="zoom:33%;" />



##### 首页转入 04

标签控件选中项字重不对<medium>

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902104217833.png" alt="image-20200902104217833" style="zoom:33%;" />



##### 首页转入 06

币种图标容器下边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902104943073.png" alt="image-20200902104943073" style="zoom:33%;" />



##### 首页转入 07

一级按钮与二级按钮样式不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902105241695.png" alt="image-20200902105241695" style="zoom:33%;" />



### 4.2.3.2 - QR扫码

##### QR扫码 01

遮罩透明度不对  3

可视区垂直位置不对 3

手电筒开关图标未实现

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902110146024.png" alt="image-20200902110146024" style="zoom:33%;" />



##### QR扫码 02

关闭按钮下边距不对   3

二级按钮颜色不对  

二级按钮字体不对  

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200902110504268.png" alt="image-20200902110504268" style="zoom:33%;" />



##### QR扫码 024 无支持

部分支持及无支持未展现 待查



##### QR扫码 04

状态未展现 待查



##### QR扫码 05

状态未展现 待查



##### QR扫码 06

状态未展现 待查