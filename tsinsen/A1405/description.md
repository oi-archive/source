<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Berland的经济状况可以用一个n行m列的表格来描述。表格中的格子所包含的数字表示Berland某个时期是否盈利，1表示盈利，-1表示亏损。 但是很不幸，这一份表格损毁了，已经看不清某些格子上面写了什么数字。而且有一个奇怪的规律：还可以分辨出的格子的数目k严格小于n和m中的最大值。除此以外，每一列、每一行的数的积都是-1（也就是每一行每一列都包含奇数个-1）。你的任务是：已知剩余的格子，求出有多少种可能的表格。答案模P。</div>
# 输入格式

<div class="pdcont">　　第一行包含两个整数n和m，分别表示表格的行数和列数。<br/>
　　第二行包含一个整数k，表示已经填好的格子数。<br/>
　　第三行开始共k行，每行三个整数x,y,c表示第x行第y列已经填了c。（保证1≤x≤n,1≤y≤m,c=1或-1）<br/>
　　最后一行包含一个整数P。</div>
# 输出格式

<div class="pdcont">　　一行一个整数表示合法的表格数。</div>
# 样例输入

<div class="pddata">2 2<br/>
0<br/>
100</div>
# 样例输出

<div class="pddata">2</div>
# 样例输入

<div class="pddata">2 2<br/>
1<br/>
1 1 -1<br/>
100</div>
# 样例输出

<div class="pddata">1</div>
# 数据规模和约定

<div class="pdcont">　　1≤n,m≤1000, 0≤k&lt;max(n,m), 2≤P≤1,000,000,007<br/>
　　对于30%的数据n*m不超过25。<br/>
　　保证k个格子的(x,y)两两不同。</div>

</div>