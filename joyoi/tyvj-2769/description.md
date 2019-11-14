# 

 
 # 题目描述 
<p>
桌上有4 堆糖果，每堆有N 颗糖，鲍比有一个最多可以装5颗糖的小篮子。他每次选择一堆糖果，把最顶上的一颗拿到篮子里。如果篮子里有两颗颜色相同的糖果，鲍比就把它们从篮子里拿出来放到自己的口袋里。如果篮子满了而里面又没有相同颜色的糖果游戏结束。口袋里的糖果就归他了。当然如果鲍比足够聪明，他同样有可能把堆里的所有糖果都拿走。<br>例如当N=5 的时候游戏可以这样进行:<br><br><center><img src="/source/joyoi/tyvj-2769/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc2OS9wcm9ibGVtc19pbWFnZXMvMzI4OS9wZy5naWY=.gif"></img></center><br>(注意上图的游戏并未结束)<br>不同的数字代表不同的颜色，颜色最多20种,编号为1..20.<br>为了拿到尽量多的糖果，他该怎么做呢？<br></p> 

 
 # 输入格式 
<p>
第一行包含一个整数N(1<=N<=40) ,代每堆所含的糖果数目。以下N 行每行包含四个1 到20 之间的正整数Xi1,Xi2,Xi3,Xi4 代表相应位置上糖果的颜色。</p> 

 
 # 输出格式 
<p>
输出一行包含口袋中的糖果的对数的最大可能值。</p> 

 
 # 提示 
<p>
数据规模：<br>对于40%的数据，1≤N≤20，出现的颜色数目T<=10<br>对于100%数据，如题目所说。<br><br></p> 
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
<tr><td>输入样例1
5
1 2 3 4
1 5 6 7
2 3 3 3
4 9 8 6
8 7 2 1

输出样例1
8

输入样例2：
1
1 2 3 4

输出样例2：
0

输入样例3：
3
1 2 3 4
5 6 7 8
1 2 3 4

输出样例3：
3

</td><td>（见上）</td></tr></table>
