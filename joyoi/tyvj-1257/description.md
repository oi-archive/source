# 

 
 # 题目背景 
NOI2010&nbsp;&nbsp;DAY1&nbsp;&nbsp;NO.3<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;YT市是一个规划良好的城市，城市被东西向和南北向的主干道划分为n×n个区域。简单起见，可以将YT市看作一个正方形，每一个区域也可看作一个正方形。从而，YT城市中包括(n+1)×(n+1)个交叉路口和2n×(n+1)条双向道路（简称道路），每条双向道路连接主干道上两个相邻的交叉路口。下图为一张YT市的地图(n&nbsp;=&nbsp;2)，城市被划分为2×2个区域，包括3×3个交叉路口和12条双向道路。<BR><img src="/source/joyoi/tyvj-1257/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI1Ny9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvMTI1Ny0xLmpwZw==.jpg" border=0 align=middle>&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;小Z作为该市的市长，他根据统计信息得到了每天上班高峰期间YT市每条道路两个方向的人流量，即在高峰期间沿着该方向通过这条道路的人数。每一个交叉路口都有不同的海拔高度值，YT市市民认为爬坡是一件非常累的事情，每向上爬h的高度，就需要消耗h的体力。如果是下坡的话，则不需要耗费体力。因此如果一段道路的终点海拔减去起点海拔的值为h(注意h可能是负数)，那么一个人经过这段路所消耗的体力是max{0,&nbsp;h}（这里max{a,&nbsp;b}表示取a,&nbsp;b两个值中的较大值）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小Z还测量得到这个城市西北角的交叉路口海拔为0，东南角的交叉路口海拔为1(如上图所示)，但其它交叉路口的海拔高度都无法得知。小Z想知道在最理想的情况下（即你可以任意假设其他路口的海拔高度），每天上班高峰期间所有人爬坡所消耗的总体力和的最小值。<BR><BR> 

 
 # 输入格式 
第一行包含一个整数n，含义如上文所示。<BR>接下来4n(n&nbsp;+&nbsp;1)行，每行包含一个非负整数分别表示每一条道路每一个方向的人流量信息。输入顺序：n(n&nbsp;+&nbsp;1)个数表示所有从西到东方向的人流量，然后n(n&nbsp;+&nbsp;1)个数表示所有从北到南方向的人流量，n(n&nbsp;+&nbsp;1)个数表示所有从东到西方向的人流量，最后是n(n&nbsp;+&nbsp;1)个数表示所有从南到北方向的人流量。对于每一个方向，输入顺序按照起点由北向南，若南北方向相同时由西到东的顺序给出(参见样例输入)。<BR><BR> 

 
 # 输出格式 
输出文件altitude.out仅包含一个数，表示在最理想情况下每天上班高峰期间所有人爬坡所消耗的总体力和（即总体力和的最小值），结果四舍五入到整数。<BR> 

 
 # 提示 
【样例说明】<BR>样例数据见下图。<BR>&nbsp;<img src="/source/joyoi/tyvj-1257/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI1Ny9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvMTI1Ny0yLmpwZw==.jpg" border=0 align=middle>&nbsp;<BR>最理想情况下所有点的海拔如上图所示。<BR>【数据规模】<BR>对于20%的数据：n&nbsp;≤&nbsp;3；<BR>对于50%的数据：n&nbsp;≤&nbsp;15；<BR>对于80%的数据：n&nbsp;≤&nbsp;40；<BR>对于100%的数据：1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;500，0&nbsp;≤&nbsp;流量&nbsp;≤&nbsp;1,000,000且所有流量均为整数。<BR>【提示】<BR>海拔高度不一定是整数。<BR><BR> 
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
<tr><td>1
1
2
3
4
5
6
7
8

</td><td>3
</td></tr></table>
