# 

 
 # 题目背景 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">话说tjx和rxt终于结束了他们16年的爱情长跑，在15岁那年举办了婚礼。</span></p> 

 
 # 题目描述 
<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">身为社会名流的tjx自然邀请到了许多嘉宾，并按照他们的意愿为他们安排了座位表。然而他调皮的同学lwx由于嫉妒过度，故意把他的座位表打乱了</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">tjx邀请的嘉宾都有点奇怪，他们不在意自己前后的位置改变了多少，但他们很在意别人与他们的左右次序。也就是说，如果A本来在B的左边，但现在A在B的右边，那么这一对嘉宾就会贡献一点不满值</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">tjx虽然很有钱，但也不想得罪这些朋友。所以，他想让你帮他算算这些嘉宾的不满值？</p> 

 
 # 输入格式 
<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">第一行一个正整数n，代表嘉宾的个数</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">第二行一个长长的字符串，代表原来的座位表</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">第三行一个长长的字符串，代表被打乱的座位表</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">每个嘉宾之间用空格隔开</p> 

 
 # 输出格式 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">一个整数，代表这些嘉宾的不满值</span></p> 

 
 # 提示 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">n&le;200000，每个嘉宾名字均为大小写字母且长度&le;5</span></p>

<p>&nbsp;</p>

<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">这个题目面板面板没有样例数据=&nbsp;=那我就手打一个数据，方便大家测试</span></p>

<p>【Input】</p>

<p>3</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">Billy&nbsp;King&nbsp;TJX</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">TJX&nbsp;King&nbsp;Billy</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">【Output】</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">3</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">【测试数据解释】</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">Billy与King&nbsp;&nbsp;Billy与TJX&nbsp;TJX与King</p> 
