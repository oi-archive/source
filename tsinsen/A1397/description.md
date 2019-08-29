<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Bob发明了一种与树有关的游戏（友情提醒：树是一个没有环的连通图）：他从树中删除任意数量（可以为0）的边，计算删除后<br/>
<br/>
　　所有连通块大小的乘积，Bob将得到这么多的分数。你的任务就是对于一颗给定的树，求出Bob能得到的最大分数。</div>
# 输入格式

<div class="pdcont">　　第一行一个整数n，表示树的节点个数。<br/>
　　接下来n-1行，每行两个整数a[i],b[i](1&lt;=a[i],b[i]&lt;=n)，表示a[i]与b[i]之间连边。<br/>
　　保证输入的图是一棵树。</div>
# 输出格式

<div class="pdcont">　　输出一个整数，表示Bob能得到的最大分数。</div>
# 样例输入

<div class="pddata">样例1：<br/>
5<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
样例2：<br/>
8<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
3 6<br/>
3 7<br/>
6 8<br/>
样例3：<br/>
3<br/>
1 2<br/>
1 3</div>
# 样例输出

<div class="pddata">样例1：<br/>
6<br/>
样例2：<br/>
18<br/>
样例3：<br/>
3</div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据，1&lt;=n&lt;=5；<br/>
　　对于30%的数据，1&lt;=n&lt;=100；<br/>
　　另有30%的数据，保证数据是一条链。<br/>
　　对于100%的数据，1&lt;=n&lt;=700；</div>

</div>