# 

 
 # 题目描述 
<p>
探险者拉罗最近发现了一个远古的宫殿，该宫殿可以表示为N×N个格子的迷宫，其中有一个格子是入口（用E表示），一个格子是出口（用X表示），有若干个格子是藏金点（用G表示），有若干个格子是障碍物（用#表示），其他格子都有怪物在里面（用-表示）。拉罗由入口开始探险，希望到达尽量多的藏金点，然后由出口离开。当然，障碍物是不能通过的。而且，由于那些远古的怪物异常凶狠，一旦被它们发现，拉罗必死无疑。幸运的是，经过多年的磨练，拉罗练就了一身非凡的本领，其中有一招叫做潜行，当她使用潜行经过有怪物的格子时，怪物是不会发现她的。不幸的是，她不能连续潜行太久，不然就会窒息，准确来说，她最多可以连续潜行着经过M个有怪物的格子。现在拉罗手头上已经有整个迷宫的地图，她需要规划出一条完整的行动路线，希望访问到尽量多的藏金点，在保证访问最多个藏金点的基础上，她还希望潜行的总时间最少（走一格为1个单位时间）。你可以帮助她吗？

 
 # 输入格式 
<p>
输入第一行是两个整数N（1 <= N <= 100）和M（1 <= M <= 200），分别表示迷宫的边长和拉罗最多可以连续潜行的格子数。

 
 # 输出格式 
<p>
输出一行，包含两个整数，分别是可以访问到的最多的藏金点数和在访问最多藏金点的基础上所需的最少的潜行总时间，两个整数之间用一个空格隔开。</p> 

 
 # 提示 
<p>
对于50%的数据，藏金点G不超过8个。</p> 
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
<tr><td>3 1
E-G
#G-
--X
</td><td>2 3</td></tr></table>