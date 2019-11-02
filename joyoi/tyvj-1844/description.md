# 

 
 # 题目背景 
JSOI2009第二轮一试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;WJJ喜欢“魔兽争霸”这个游戏。在游戏中，巫妖是一种强大的英雄，它的技能Frozen&nbsp;Nova每次可以杀死一个小精灵。我们认为，巫妖和小精灵都可以看成是平面上的点。<BR>&nbsp;&nbsp;&nbsp;&nbsp;当巫妖和小精灵之间的直线距离不超过R，且巫妖看到小精灵的视线没有被树木阻挡（也就是说，巫妖和小精灵的连线与任何树木都没有公共点）的话，巫妖就可以瞬间杀灭一个小精灵。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在森林里有N个巫妖，每个巫妖释放Frozen&nbsp;Nova之后，都需要等待一段时间，才能再次施放。不同的巫妖有不同的等待时间和施法范围，但相同的是，每次施放都可以杀死一个小精灵。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在巫妖的头目想知道，若从0时刻开始计算，至少需要花费多少时间，可以杀死所有的小精灵？&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件第一行包含三个整数N、M、K(N,M,K&lt;=200)，分别代表巫妖的数量、小精灵的数量和树木的数量。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行包含四个整数x,&nbsp;y,&nbsp;r,&nbsp;t，分别代表了每个巫妖的坐标、攻击范围和施法间隔（单位为秒）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;再接下来M行，每行两个整数x,&nbsp;y，分别代表了每个小精灵的坐标。<BR>&nbsp;&nbsp;&nbsp;&nbsp;再接下来K行，每行三个整数x,&nbsp;y,&nbsp;r，分别代表了每个树木的坐标。<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入数据中所有坐标范围绝对值不超过10000，半径和施法间隔不超过20000。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出一行，为消灭所有小精灵的最短时间（以秒计算）。如果永远无法消灭所有的小精灵，则输出-1。 
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
<tr><td>2 3 1
-100 0 100 3
100 0 100 5
-100 -10
100 10
110 11
5 5 10</td><td>5</td></tr></table>
