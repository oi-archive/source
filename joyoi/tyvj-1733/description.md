# 

 
 # 题目背景 
APIO2011&nbsp;T2<BR> 

 
 # 题目描述 
TooDee是一块二维格子状的土地（就像著名的笛卡尔坐标系那样），在这里生活着很多可爱的Dee。Dee是像蜜蜂一样的小动物，它们只在二维活动，而且它们非常的文明开化。TooDee的蜂窝和正常世界的蜂窝也是很不一样的，它们是矩形的且它们的边平行于TooDee的地理坐标系，就是说矩形的边或者是东西走向，或者是南北走向。&nbsp;<BR>因为Dees是很高级的生物，它们有很多固定的飞行轨道，这些轨道由一些平行于坐标轴的线段组成，线段只会在经纬度都是整数的点相交。Dee在TooDee飞行时必须遵守以下规则（请记住TooDee中所有点的经纬度都是整数）：&nbsp;<BR>如果当前在点(XS,&nbsp;YS)，则下步只能飞到四个邻点&nbsp;(XS,&nbsp;YS&nbsp;–&nbsp;1),&nbsp;(XS,&nbsp;YS&nbsp;+&nbsp;1),&nbsp;(XS&nbsp;–&nbsp;1,&nbsp;YS&nbsp;),&nbsp;(XS&nbsp;+&nbsp;1,&nbsp;YS&nbsp;)；&nbsp;<BR>不可以进入蜂巢；&nbsp;<BR>只能在蜂巢的角或者边上改变飞行方向；&nbsp;<BR>开始的时候可以向任何方向飞；&nbsp;<BR><BR>今晚是公共财政大臣Deeficer的女儿的生日，她想尽早回家，请帮她找到最快的回家路径。假设她每秒可以飞行一个单位的距离。<BR> 

 
 # 输入格式 
每个测试点包含多组数据。<BR>输入的第一行包含一个整数T，表示测试数据的组数。接下来依次描述这T组数据，相邻的两组之间使用一个空行分隔。测试数据不多于20组。<BR>对于每组数据，第一行包含4个整数xs,&nbsp;ys,&nbsp;xt,&nbsp;yt，表示Deeficer的办公室和家的坐标分别为(xs,&nbsp;ys)和(xt,&nbsp;yt)。第二行包含一个整数n，表示蜂巢的个数。接下来的n行描述所有的蜂巢，其中第i行包含4个整数xi1,&nbsp;yi1,&nbsp;xi2,&nbsp;yi2，表示第i个蜂巢两个对角的坐标分别为(xi1,&nbsp;yi1)和(xi2,&nbsp;yi2)。<BR>任何两个蜂巢都不会相交，也不会接触（在角上也不会接触）。办公室和家处在不同的位置。每个蜂巢的面积为正。 

 
 # 输出格式 
对于每一组数据，输出一个整数，表示Deeficer最快回家的时间（单位为秒），如果她无法按规则回家，则输出“No&nbsp;Path”。 

 
 # 提示 
对于20%的测试数据，n&nbsp;≤&nbsp;10，所有的坐标都是小于100的非负整数；<BR>对于60%的测试数据，n&nbsp;≤&nbsp;100，所有坐标的绝对值都小于1000；<BR>对于100%的测试数据，1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;1000，所有坐标都是不超过10^9的整数； 
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
<tr><td>2

1 7 7 8
2
2 5 3 8
4 10 6 7

2 1 5 4
1
3 1 4 3</td><td>9
No Path</td></tr></table>
