<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　MST (Meaningless State Team) 公司在Berland赢得了一个重要的修复项目的投标。<br/>
　　在Berland有n个城市，m条道路，一些城市之间有道路连接。每个道路都有一个权值，而且没有方向限制。MST小组应该对某些道路执行修复工作，使得任意两个城市能只通过修复了的道路就能联通。此外，被修复的道路里应该正好包括K条与1连接的路。<br/>
　　请你找出使得满足条件的权值和最小的修复道路集合。</div>
# 输入格式

<div class="pdcont">　　第一行包括3个数，n,m,k。<br/>
　　下面m行，每行三个数ai,bi,wi，表示一条权值为wi的道路连接ai和bi。<br/>
　　保证没有重边和自环。</div>
# 输出格式

<div class="pdcont">　　第一行输出集合大小，第二行输出你求出的道路集合。如果没有满足条件的道路集合，输出-1。</div>
# 样例输入

<div class="pddata">4 5 2<br/>
1 2 1<br/>
2 3 1<br/>
3 4 1<br/>
1 3 3<br/>
1 4 2</div>
# 样例输出

<div class="pddata">3<br/>
1 5 2</div>
# 数据规模和约定

<div class="pdcont">　　20% n &lt;= 10,m &lt;= 30<br/>
　　50% n &lt;= 100,m &lt;= 1000<br/>
　　70% n &lt;= 1000,m &lt;= 10000<br/>
　　100% 1 &lt;= n &lt;= 5000,0 &lt;= m &lt;= 100000,0&lt;= k &lt;= n,1 &lt;= w &lt;= 100000</div>

</div>