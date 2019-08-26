
# Description

<div class="content">Byte City 的街道形成了一个标准的棋盘网络 – 他们要么是北南走向要么就是西东走向. 北南走向的路口从 1 到 n编号, 西东走向的路从1 到 m编号. 每个路口用两个数(i, j) 表示(1 &lt;= i &lt;= n, 1 &lt;= j &lt;= m). 
Byte City里有一条公交线, 在某一些路口设置了公交站点. 公交车从 (1, 1) 发车, 在(n, m)结束.公交车只能往北或往东走. 现在有一些乘客在某些站点等车. 公交车司机希望在路线中能接到尽量多的乘客.帮他想想怎么才能接到最多的乘客. 
</div>

# Input

<div class="content">第一行三个数n, m 和 k – 表示北南走向的路的个数以及西东走向的路和乘客等车的站点的个数. ( 1 &lt;= n &lt;= 10^9, 1 &lt;= m &lt;= 10^9, 1 &lt;= k &lt;= 10^5). 
接下来k 行每行描述一个公交站的信息.第 i + 1 行三个正整数 xi, yi 和 pi, 1 &lt;= xi &lt;= n, 1 &lt;= yi &lt;= m, 1 &lt;= pi &lt;= 10^6. 表示在(xi, yi) 有 pi 个乘客在等车. 每个路口在数据中最多出现一次,乘客总数不会超过1 000 000 000. 
</div>

# Output

<div class="content">一个数表示最多能接到的乘客数量. 

</div>

# Sample Input

<div class="content"><span class="sampledata">8 7 11<br/>
4 3 4<br/>
6 2 4<br/>
2 3 2<br/>
5 6 1<br/>
2 5 2<br/>
1 5 5<br/>
2 1 1<br/>
3 1 1<br/>
7 7 1<br/>
7 4 2<br/>
8 6 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

