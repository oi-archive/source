# 

 
 # 题目背景 
APIO2010 

 
 # 题目描述 
信号覆盖&nbsp;<BR>【问题描述】&nbsp;<BR>&nbsp;&nbsp;&nbsp;一家电信公司正在北京城搭建一个&nbsp;GSM&nbsp;网络。城市里共有&nbsp;n&nbsp;个房子需要被信号覆盖。由于经费的限制，电信公司只能安装一个天线。&nbsp;<BR>&nbsp;&nbsp;&nbsp;这里将每个房子用一个点坐标来表示。为了简化天线的放置，电信公司将会选择其中的3个房子作一个外接圆，然后将天线放在圆的中心，所有位于这个圆内或者圆的边界上的房子都将被天线的信号所覆盖。&nbsp;<BR>&nbsp;&nbsp;&nbsp;电信公司将会随机选择城市中的3个房子来搭建天线，他们想知道在所有可能放置天线的方案中平均会有多少个房子被信号覆盖。&nbsp;<BR>&nbsp;&nbsp;&nbsp;例如，假设共有&nbsp;4个房子A,&nbsp;B,&nbsp;C,&nbsp;D，它们的位置如下图：&nbsp;<BR><BR><img src="/source/joyoi/tyvj-1217/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIxNy9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzEyMTcuanBn.jpg" border=0 align=middle><BR>&nbsp;<BR>&nbsp;&nbsp;&nbsp;如果我们选择ABC或者BCD三个点搭建的外接圆，所有的房子都会被覆盖。如果我们选择ACD&nbsp;或者ABD，剩下的房子将不会在天线的信号覆盖范围内。因此平均有(4&nbsp;+&nbsp;4&nbsp;+&nbsp;3&nbsp;+&nbsp;3)&nbsp;/&nbsp;4&nbsp;=&nbsp;3.50&nbsp;个房子被信号覆盖。&nbsp;<BR>&nbsp;&nbsp;&nbsp;给定所有房子的位置，你的任务是计算平均有多少个房子被信号覆盖。假定每一个房子都有一个二维的整数坐标，并且保证任何三个房子都不在同一条直线上，任何四个房子都不在同一个圆上。&nbsp;<BR> 

 
 # 输入格式 
输入第一行包含一个正整数&nbsp;n,&nbsp;表示房子的总数。接下来有&nbsp;n&nbsp;行，分别表示每一个房子的位置。对于&nbsp;i&nbsp;=&nbsp;1,&nbsp;2,&nbsp;..,&nbsp;n,&nbsp;第i&nbsp;个房子的坐标用一对整数&nbsp;xi和yi来表示，中间用空格隔开。 

 
 # 输出格式 
输出文件包含一个实数，表示平均有多少个房子被信号所覆盖，保留两位小数 

 
 # 提示 
【数据范围】&nbsp;<BR>100%的数据保证，对于&nbsp;i&nbsp;&nbsp;=&nbsp;1,&nbsp;2,&nbsp;..,&nbsp;&nbsp;n,&nbsp;第&nbsp;i&nbsp;个房子的坐标(xi,&nbsp;&nbsp;yi)为整数且&nbsp;–1,000,000&nbsp;≤&nbsp;xi,&nbsp;yi&nbsp;≤&nbsp;1,000,000.&nbsp;任何三个房子不在同一条直线上，任何四个房子不在同一个圆上；&nbsp;<BR>40%的数据，n&nbsp;≤&nbsp;100；&nbsp;<BR>70%的数据，n&nbsp;≤&nbsp;500；&nbsp;<BR>100%的数据，3&nbsp;≤&nbsp;n&nbsp;≤&nbsp;1,500。 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 
0 2 
4 4 
0 0 
2 0 
</td><td>3.50</td></tr></table>
