# 

 
 # 题目背景 
NOIP2011&nbsp;day2&nbsp;第三题<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;风景迷人的小城Y&nbsp;市，拥有n&nbsp;个美丽的景点。由于慕名而来的游客越来越多，Y&nbsp;市特意安排了一辆观光公交车，为游客提供更便捷的交通服务。观光公交车在第&nbsp;0&nbsp;分钟出现在&nbsp;1号景点，随后依次前往&nbsp;2、3&nbsp;、4&nbsp;……n&nbsp;号景点。从第&nbsp;i&nbsp;号景点开到第&nbsp;i+1&nbsp;号景点需要&nbsp;Di&nbsp;分钟。<BR>任意时刻，公交车只能往前开，或在景点处等待。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;设共有m&nbsp;个游客，每位游客需要乘车1&nbsp;次从一个景点到达另一个景点，第i&nbsp;位游客在Ti&nbsp;分钟来到景点&nbsp;Ai&nbsp;，希望乘车前往景点Bi&nbsp;（Ai&lt;B<BR>i&nbsp;）。为了使所有乘客都能顺利到达目的地，公交车在每站都必须等待需要从该景点出发的所有乘客都上车后才能出发开往下一景点。假设乘客上下车不需要时间。&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;一个乘客的旅行时间，等于他到达目的地的时刻减去他来到出发地的时刻。因为只有一辆观光车，有时候还要停下来等其他乘客，乘客们纷纷抱怨旅行时间太长了。于是聪明的司机ZZ给公交车安装了&nbsp;k&nbsp;个氮气加速器，每使用一个加速器，可以使其中一个&nbsp;Di&nbsp;减1&nbsp;。对于<BR>同一个Di&nbsp;可以重复使用加速器，但是必须保证使用后Di&nbsp;大于等于0&nbsp;。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;那么ZZ该如何安排使用加速器，才能使所有乘客的旅行时间总和最小？&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第1&nbsp;行是3&nbsp;个整数n,&nbsp;m,&nbsp;k&nbsp;，每两个整数之间用一个空格隔开。分别表示景点数、乘客数和氮气加速器个数。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2&nbsp;行是n-1&nbsp;个整数，每两个整数之间用一个空格隔开，第i&nbsp;个数表示从第i&nbsp;个景点开往第i+1&nbsp;个景点所需要的时间，即&nbsp;Di&nbsp;。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;第3&nbsp;行至m+2&nbsp;行每行3&nbsp;个整数&nbsp;Ti&nbsp;,&nbsp;Ai,&nbsp;Bi，每两个整数之间用一个空格隔开。第&nbsp;i+2&nbsp;行表示第i&nbsp;位乘客来到出发景点的时刻，出发的景点编号和到达的景点编号。&nbsp; 

 
 # 输出格式 
共一行，包含一个整数，表示最小的总旅行时间。&nbsp; 

 
 # 提示 
&nbsp;&nbsp;对于10%&nbsp;的数据，k=0&nbsp;；&nbsp;<BR>&nbsp;&nbsp;对于20%&nbsp;的数据，k=1&nbsp;；&nbsp;<BR>&nbsp;&nbsp;对于40%&nbsp;的数据，2&nbsp;≤&nbsp;n&nbsp;≤&nbsp;50，1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;1,000，0&nbsp;≤&nbsp;k&nbsp;≤&nbsp;20，0&nbsp;≤&nbsp;Di&nbsp;≤&nbsp;10，0&nbsp;≤&nbsp;T&nbsp;i&nbsp;≤&nbsp;500；&nbsp;<BR>&nbsp;&nbsp;对于60%&nbsp;的数据，1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;100，1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;1,000，0&nbsp;≤&nbsp;k&nbsp;≤&nbsp;100&nbsp;，0&nbsp;≤&nbsp;Di&nbsp;≤&nbsp;100，0&nbsp;≤&nbsp;T&nbsp;i&nbsp;≤&nbsp;10,000&nbsp;；&nbsp;<BR>&nbsp;&nbsp;对于100%的数据，1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;1,000，1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;10,000&nbsp;，0&nbsp;≤&nbsp;k&nbsp;≤&nbsp;100,000，0&nbsp;≤&nbsp;Di&nbsp;≤&nbsp;100&nbsp;，0&nbsp;≤&nbsp;T&nbsp;i&nbsp;≤&nbsp;100,000。&nbsp; 
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
<tr><td>3 3 2 
1 4 
0 1 3 
1 1 2 
5 2 3 </td><td>10 

对D2 使用2 个加速器，从2 号景点到 3 号景点时间变为 2 分钟。 
公交车在第1 分钟从1 号景点出发，第2 分钟到达2 号景点，第5 分钟从2 号景点出发，
第7 分钟到达 3 号景点。 
第1 个旅客旅行时间 7-0 = 7 分钟。 
第2 个旅客旅行时间 2-1 = 1 分钟。 
第3 个旅客旅行时间 7-5 = 2 分钟。 
总时间 7+1+2 = 10分钟。 </td></tr></table>
