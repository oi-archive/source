# 

 
 # 题目背景 
在晚饭克星的陪同下，DL的晚饭果然又去到了少数人的手中。但现在，DL担心的不是晚饭，而是如何尽快到达中山一中，避免错失最后一次NOIP的参赛机会。杯具的是，MM小队迷路了……<BR> 

 
 # 题目描述 
幸好，上帝是公平的，他告诉MM小队，还有N个路口就可以到达中山一中，并且车上有M个人拥有电子地图，他们可以引导司机选择正确的路线。但遗憾的是，MM小队的同学表达水平有一点缺憾，而且司机的记忆力也是有限的，所以每到达一个路口，就要叫一个同学花T时间去向司机描述到达下个路口的正确路线，当然，同学也会累的，一个同学最多描述K个路口的状况后就必须换班（当然不必描述完K个路口才换班）歇息至少一个单位时间，而换班也是需要时间的，这个时间为常数L。现在Ghost需要事先安排好顺序让同学们引导司机，当然，要求在最短的时间内到达。<BR> 

 
 # 输入格式 
第一行，N&nbsp;M&nbsp;K&nbsp;L，含义如题目所述<BR>接下来的N行，每行M个整数，第i行第j个数表示第j个同学在第i个路口向司机描述路况所需的时间<BR><BR> 

 
 # 输出格式 
一个数，到达中山一中所需的最少时间<BR>接下来，为选派同学的顺序，格式如下：<BR>Road=[1]&nbsp;Stu=[2]&nbsp;Step=[3]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<BR>[1]为路口编号&nbsp;&nbsp;&nbsp;[2]为同学编号&nbsp;&nbsp;&nbsp;[3]此同学此次指导司机行驶路口数量<BR>含义为，在第[1]个路口开始，由编号为[2]的同学，指导司机行驶[3]个路口<BR>若有多种顺序可取最小值则按Stu的值为字典顺序输出。<BR>保证有唯一解<BR><BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1284/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI4NC9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL3AxMjg0LmpwZw==.jpg" border=0 align=middle><BR>如图，有两种选派方法可以取得最优值，分别是：<BR>【蓝线】第1个路口开始由第2位同学指路1次<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第2个路口开始由第4位同学指路3次<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第5个路口开始由第2位同学指路一次<BR><BR>【红线】第1个路口开始由第2位同学指路1次<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第2个路口开始由第5位同学指路3次<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第5个路口开始由第2位同学指路一次<BR>由于按字典顺序输出，所以选取蓝色线顺序。<BR><BR>&nbsp;0&lt;N&lt;=200<BR>0&lt;M&lt;=80<BR>0&lt;K&lt;=50<BR>0&lt;L&lt;=100<BR>0&lt;T&lt;=100<BR><BR> 
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
<tr><td>5 5 3 2
3 1 5 3 3
4 4 5 1 1
3 5 4 2 2
5 5 2 2 2
5 5 2 3 3

</td><td>12
Road=1 Stu=2 Step=1
Road=2 Stu=4 Step=3
Road=5 Stu=3 Step=1

</td></tr></table>
