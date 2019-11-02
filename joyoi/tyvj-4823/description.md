# 

 
 # 题目背景 
<h1>猩猩可不傻</h1>

<h1><span style="color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; font-size: 16px; line-height: 1.5;">在一条没有分岔的高速公路上有n个关</span><span style="color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; font-size: 16px; line-height: 1.5;">口，相邻两个关口之间的距离都是10km。所有车辆在这条高速公路上的最低速度为60km/h，最高速度为120km/h，并且只能在关口处改变速度。巡逻的方式是在某个时刻Ti从第ni个关口派出一辆巡逻车匀速驶抵第(ni+1)个关口，路上耗费的时间为ti秒。</span></h1>

<h4 style="box-sizing: inherit; margin: 0px; padding: 0.3em 0px; line-height: 1.5; font-size: 16px; color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; background-color: rgb(255, 255, 255);">两辆车相遇是指它们之间发生超车或者两车同时到达某关口（同时出发不算相遇）。</h4>

<h4 style="box-sizing: inherit; margin: 0px; padding: 0.3em 0px; line-height: 1.5; font-size: 16px; color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; background-color: rgb(255, 255, 255);">猩猩们想知道一辆于6点整从第1个关口出发去第n个关口的车（称为目标车）最少会与多少辆巡逻车相遇，请编程计算之。假设所有车辆到达关口的时刻都是整秒。</h4> 

 
 # 题目描述 
<h4 style="font-weight: normal; line-height: 1.5; box-sizing: inherit; margin: 0px; padding: 0.3em 0px; font-size: 16px; color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; background-color: rgb(255, 255, 255);">两辆车相遇是指它们之间发生超车或者两车同时到达某关口（同时出发不算相遇）。</h4>

<h4 style="font-weight: normal; line-height: 1.5; box-sizing: inherit; margin: 0px; padding: 0.3em 0px; font-size: 16px; color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; background-color: rgb(255, 255, 255);">猩猩们想知道一辆于6点整从第1个关口出发去第n个关口的车（称为目标车）最少会与多少辆巡逻车相遇，请编程计算之。假设所有车辆到达关口的时刻都是整秒。</h4> 

 
 # 输入格式 
<p>请在此填写输<span style="color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; font-size: 16px; line-height: 24px; background-color: rgb(255, 255, 255);">输入第一行为两个用空格隔开的整数，分别为关口数n和巡逻车数m。（1&lt;n&lt;50,1&lt;m&lt;300），接下来的m行每一行为一辆巡逻车的信息（按出发位置递增排序），格式为ni　Ti　ti，三项用空格隔开，分别表示第i辆巡逻车的出发位置、出发时刻和路上耗费的时间，其中ni和ti为整数，Ti形如hhmmss，表示时、分、秒，采用24小时制，不足两位的数用前置0补齐。（1&lt;=ni&lt;n,05:00:00&lt;=Ti&lt;=23:00:00,300&lt;=ti&lt;=600</span>入格式</p> 

 
 # 输出格式 
<p>请在此填写输出格式<span style="color: rgb(85, 85, 85); font-family: 'Open Sans', Seravek, 'Segoe UI', Verdana, 'PingFang SC', 'Hiragino Sans GB', 'Lantinghei SC', 'Microsoft Yahei', 'WenQuanYi Micro Hei', sans; font-size: 16px; line-height: 24px; background-color: rgb(255, 255, 255);">输出第一行为目标车与巡逻车相遇次数。第二行为目标车与巡逻车相遇次数最少时最早到达第n个关口的时刻（格式同输入中的Ti）。</span></p> 
