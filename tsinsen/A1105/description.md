<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在一个地图上有$$N$$个地窖（$$N\le 12$$），每个地窖中埋有一定数量的地雷。同时，给出地窖之间的连接路径。</div>
# 题目要求

<div class="pdcont">　　当地窖及其连接的数据给出之后，某人可以从任一处开始挖地雷，每个地窖只能经过一次，然后可以沿着指出的连接往下挖（仅能选择一条路径），当无连接时挖地雷工作结束。设计一个挖地雷的方案，使某人能挖到最多的地雷。</div>
# 输入格式

<div class="pdcont">　　第一行一个数$$N$$。<br/>
　　第二行$$N$$个数$$w_i$$表示每个点的地雷数。<br/>
　　随后$$N-1$$行若干个数。第$$i$$行第$$j$$个数表示$$i$$与$$i+j$$是否连通。1为连通，0为不连通。</div>
# 输出格式

<div class="pdcont">　　$$K_1$$--$$K_2$$--$$\cdots$$--$$K_V$$                  （挖地雷的顺序）<br/>
　　MAX=$$ans$$                            （挖地雷的数量）<br/>
　　如果有多种方案则输出字典序最小的方案。</div>
# 样例输入

<div class="pddata">5<br/>
10 8 4 7 6<br/>
1 1 1 1<br/>
0 0 0<br/>
1 1<br/>
1</div>
# 样例输出

<div class="pddata">2-1-3-4-5<br/>
MAX=35</div>
# 数据规模和约定

<div class="pdcont">　　$$n\le 12$$</div>

</div>