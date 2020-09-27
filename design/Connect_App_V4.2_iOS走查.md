## 版本记录

|          版本           |      日期      | 阶段 |
| :---------------------: | :------------: | :--: |
| TestFlight.1.1.0(11004) | 2020年08月25日 | 一查 |

|          版本          |      日期      | 阶段 |
| :--------------------: | :------------: | :--: |
| FunctionX走查09-01.ipa | 2020年09月03日 | 二查 |



## 标注说明

| 后缀内容 | 释义               |
| :------- | :----------------- |
|          | 已查未修改         |
| 1        | 已修改待复查       |
| 2        | 无法实现待变更讨论 |
| 3        | 已修改未达标       |



## 走查内容

### 4.2.2.8 - 首页与资产详情

##### 首页 01

标题栏高度不对3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903100840585.png" alt="image-20200903100840585" style="zoom:50%;" />



##### 首页 011 滚动动效

标题字号不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903101007608.png" alt="image-20200903101007608" style="zoom:50%;" />



##### 首页 02

弹窗阴影缺失**<全局影响>** 3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903101255848.png" alt="image-20200903101255848" style="zoom:50%;" />



##### 添加资产 01

项目卡片底部圆角缺失

项目卡片圆角度数待核实<16pt/dp>

项目内容上下边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903101525068.png" alt="image-20200903101525068" style="zoom:50%;" />



##### 添加资产 012 滚动动效

滚动触发阴影未实现**<全局影响>**

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903101745609.png" alt="image-20200903101745609" style="zoom:50%;" />



##### 添加资产 02

键盘激活状态下上滑视窗顶部菜单栏动画有bug



##### 添加资产 021

主标题字重不对

项目最小高度不对

与输入框行距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903102519794.png" alt="image-20200903102519794" style="zoom:50%;" />



##### 资产详情 01

主金额字号不对<同计算器页面主金额算法：前12后18科学计数/金额动态逻辑：边距极小8pt→字号极小20pt→两折行垂直居中> 3

上半部分信息区整体高度不对

标签页拨盘交互不对

图标容器样式不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903103053659.png" alt="image-20200903103053659" style="zoom:50%;" />



##### 资产详情 03

全局模糊遮罩待统一



##### 资产详情 04

###### 拖拽排序样式不对<透明度；阴影>  2(系统样式, 无法定制)



##### 资产详情 05

关闭按钮上下行距不对 3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903103131672.png" alt="image-20200903103131672" style="zoom:50%;" />



##### 资产详情 06

###### 地址移除弹窗缺失 2(只有一个地址时没有remove, 多个地址可以remove)



##### 资产详情 07

dapp图标大小不对；圆角度数不对；文本垂直居中不对 3

收藏功能缺失 3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903103245734.png" alt="image-20200903103245734" style="zoom:50%;" />



### 4.2.5.2 - 通知中心

未走查



### 4.2.7.3 - 转出

##### 发送 03 数字货币

主金额输入动效未实现 

地址行距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903103642458.png" alt="image-20200903103642458" style="zoom:50%;" />



##### 发送 031 无效输入

最大允许输入未实现<前12后18科学计数/金额动态逻辑：边距极小8pt→字号极小20pt→两折行垂直居中> 3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903103739072.png" alt="image-20200903103739072" style="zoom:50%;" />



##### 发送 04 法币有效

###### 切换内容保留输入内容未实现 2(切换币种不保留输入)

切换内容不一致



##### 发送 05 设置手续费

一级按钮上边距不够 3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903104028790.png" alt="image-20200903104028790" style="zoom:50%;" />



##### 发送 051 设置手续费超限ETH

二级按钮警告状态颜色填充不对 1

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903115422428.png" alt="image-20200903115422428" style="zoom:50%;" />



##### 发送 06 选择接收人

标题栏标题缺失 1

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903115541419.png" alt="image-20200903115541419" style="zoom:50%;" />



##### 发送 062 选择接收人联想

联想功能缺失



##### 发送 072 接收人报错

功能未实现 3

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903115730847.png" alt="image-20200903115730847" style="zoom:50%;" />



##### 通用支付 01

关闭按钮上边距不对 1

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903120018862.png" alt="image-20200903120018862" style="zoom:50%;" />



##### 通用支付 02 并存生物优先

深色键盘下的输入框未激活样式补充<background：#1B1D41>

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903122042134.png" alt="image-20200903122042134" style="zoom:50%;" />



##### 通用支付 03 仅密码

一级按钮禁用态底边距不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903121643637.png" alt="image-20200903121643637" style="zoom:50%;" />



##### 通用支付 04 仅生物

重新生物识别弹窗未下移

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903122042134.png" alt="image-20200903122042134" style="zoom:50%;" />



### 4.2.9.1 - 转入

##### 首页转入 03

标题栏大标题状态缺失

tab控件动效缺失

tab控件距下边距不对

卡片标题币种图标容器不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903122424831.png" alt="image-20200903122424831" style="zoom:50%;" />



##### 首页转入 032 滚动动效

滚动触发标题栏阴影未实现 3



##### 首页转入 04

图标容器不对



##### 首页转入 06

图标容器不对



##### 首页转入 07

二维码边框宽度不对 3

一级按钮不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903122836529.png" alt="image-20200903122836529" style="zoom:50%;" />



### 4.2.3.2 - QR扫码

##### QR扫码 01

手电筒文本字色字重不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903123037679.png" alt="image-20200903123037679" style="zoom:50%;" />



##### QR扫码 02

关闭按钮上边距不对 3

图标容器约束不对

<img src="http://pic.arthurzhou.net/uPic/2020/image-20200903134216487.png" alt="image-20200903134216487" style="zoom:50%;" />



##### QR扫码 022 部分支持

卡片内容问题通用



##### QR扫码 023 部分支持

标题栏滚动动效bug 3



##### QR扫码 024 无支持

无资产支持状态无法展现 待查



##### QR扫码 04

其他扫码结果无法展现 待查

