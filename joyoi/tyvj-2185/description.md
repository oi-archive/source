# 

 
 # 题目描述 
<p>
在一个国家里，有n个城市（编号为0 到n-1）。这些城市之间有n条双向道<br>路相连（编号为0 到n-1），其中编号为i的道路连接了城市i和城市ri（一条道<br>路可以连接一个城市和它自身），长度为di。n 个城市中有m个拥有自己城堡，<br>可以抵御敌人侵略。如果没有城堡的城市遭受攻击，则离它最近的城堡将派兵前<br>往救援。<br>你的任务是在不超过k个没有城堡的城市中建立城堡，使得所有城市中“离<br>最近城堡的距离”的最大值尽量小。换句话说，若令dist(c)表示城市c的最近城<br>堡离它的距离，则你的任务是让max{dist(c)}尽量小。<br>输入数据保证存在方案使得对于每个城市，至少有一个城堡能够到达。<br></p> 

 
 # 输入格式 
<p>
输入第一行为三个正整数n, m, k。第二行包含n个整数r0,r1,…,rn-1。第三行<br>包含n 个整数d0,d1,…,dn-1。第四行包含m 个各不相同的0~n-1 之间的整数，分<br>别为m个城堡所在的城市编号。<br></p> 

 
 # 输出格式 
<p>
输出仅一行，包含一个整数，即max{dist(c)}的最小值。</p> 

 
 # 提示 
<p>
100%的数据满足：2<=n<=50, 1<=di<=106, 0<=m<=n-k</p> 
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
<tr><td></td><td></td></tr></table>
