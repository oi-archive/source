<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给一个N个点M条边的连通无向图，满足每条边最多属于一个环，有Q组询问，每次询问两点之间的最短路径。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含三个整数，分别表示N和M和Q<br/>
　　下接M行，每行三个整数v，u，w表示一条无向边v-u，长度为w<br/>
　　最后Q行，每行两个整数v，u表示一组询问</div>
# 输出格式

<div class="pdcont">　　输出Q行，每行一个整数表示询问的答案</div>
# 样例输入

<div class="pddata">9 10 2<br/>
1 2 1<br/>
1 4 1<br/>
3 4 1<br/>
2 3 1<br/>
3 7 1<br/>
7 8 2<br/>
7 9 2<br/>
1 5 3<br/>
1 6 4<br/>
5 6 1<br/>
1 9<br/>
5 7</div>
# 样例输出

<div class="pddata">5<br/>
6</div>
# 数据说明

<div class="pdcont">　　对于5%的数据，N&lt;=100<br/>
　　对于20%的数据，N&lt;=1000<br/>
　　对于100%的数据，N&lt;=10000，Q&lt;=10000，w&lt;=1000<br/>
　　对于100%的数据，时间限制为0.1s。</div>

</div>