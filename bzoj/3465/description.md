
# Description

<div class="content"><p><span style="font-size: medium">有一天，VFleaKing到森林里游玩，回来之后跟pyx1997说，我发现好多棵会动的树耶！<br/>
pyx1997说，这有什么好稀奇的，我用手指头就能维护每棵树的形态。<br/>
于是又过了几天VFleaKing到沙漠里游玩，回来之后跟pyx1997说，我发现好多棵会动的仙人掌耶！<br/>
pyx1997说，这有什么好稀奇的，我用脚丫子就能维护每棵仙人掌的形态。<br/>
于是VFleaKing很郁闷，他向你求助，请帮帮他吧。</span></p>
<p><span style="font-size: medium">如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。<br/>
如果一个无向图的每个连通块都是个仙人掌，且不存在自环，我们就称之为沙漠。</span></p>
<p><span style="font-size: medium">为了证明你确实能够维护仙人掌，我们给你n个结点，从1到n标号。初始时没有任何边。每次进行如下操作之一：<br/>
1. link v u w<br/>
    在结点v, u间连一条权值为w的边。1 &lt;= v, u &lt;= n且w为正整数。<br/>
    如果连边完成后图仍为沙漠，则输出&#34;ok&#34;（不含引号）。<br/>
    否则操作非法，撤销此次操作并输出&#34;failed&#34;（不含引号）。<br/>
2. cut v u w 在结点v, u间删掉权值为w的边。1 &lt;= v, u &lt;= n且w为正整数。<br/>
    如果存在这样的边则输出&#34;ok&#34;（不含引号）（如果有多条权值为w的边删去任意一条）。<br/>
    否则操作非法，不进行操作并输出&#34;failed&#34;（不含引号）。<br/>
3. distance? v u 查询结点v到结点u的最短路信息。1 &lt;= v, u &lt;= n。<br/>
    输出两个用空格隔开的整数Lm, Wm。<br/>
    Lm代表最短路的长度，Wm代表最短路上的边权的最小值。<br/>
    如果v = u则Lm = 0, Wm = 2147483647。<br/>
    如果没有路可到达则Lm = -1, Wm = -1。<br/>
    如果最短路不唯一则Wm = -1。</span></p></div>

# Input

<div class="content"><p class="MsoNormal"><span style="font-size: medium"><span style="font-family: 宋体"><br/>
</span></span></p>
<p class="MsoNormal"><span style="font-size: medium"><span style="font-family: 宋体">第一行两个用空格隔开的正整数</span><span lang="EN-US">n, m</span><span style="font-family: 宋体">表示一共有</span><span lang="EN-US">n</span><span style="font-family: 宋体">个结点，</span><span lang="EN-US">m</span><span style="font-family: 宋体">个操作。</span></span></p>
<p class="MsoNormal"><span style="font-size: medium"><span style="font-family: 宋体">接下来</span><span lang="EN-US">m</span><span style="font-family: 宋体">行，每行代表一个操作。</span></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><span style="font-family: 宋体">对于每个操作，输出相应的结果。</span></span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 49<br/>
<br/>
link 1 2 1<br/>
<br/>
link 1 2 2<br/>
<br/>
distance? 1 2<br/>
<br/>
cut 1 2 1<br/>
<br/>
link 1 2 2<br/>
<br/>
distance? 1 2<br/>
<br/>
cut 1 2 2<br/>
<br/>
cut 1 2 2<br/>
<br/>
link 3 3 2<br/>
<br/>
cut 4 4 2<br/>
<br/>
link 1 2 2<br/>
<br/>
link 1 3 3<br/>
<br/>
link 2 3 4<br/>
<br/>
distance? 1 2<br/>
<br/>
distance? 1 3<br/>
<br/>
distance? 2 4<br/>
<br/>
link 2 4 3<br/>
<br/>
link 3 5 3<br/>
<br/>
link 4 5 1<br/>
<br/>
distance? 4 5<br/>
<br/>
cut 1 2 2<br/>
<br/>
link 4 5 5<br/>
<br/>
distance? 1 5<br/>
<br/>
cut 2 3 4<br/>
<br/>
link 2 5 5<br/>
<br/>
link 1 5 2<br/>
<br/>
distance? 1 2<br/>
<br/>
cut 4 5 5<br/>
<br/>
distance? 1 2<br/>
<br/>
cut 3 5 3<br/>
<br/>
distance? 1 2<br/>
<br/>
cut 2 5 5<br/>
<br/>
distance? 1 2<br/>
<br/>
distance? 4 5<br/>
<br/>
link 3 5 2<br/>
<br/>
distance? 1 3<br/>
<br/>
distance? 4 3<br/>
<br/>
link 4 6 3<br/>
<br/>
link 2 6 1<br/>
<br/>
distance? 2 6<br/>
<br/>
distance? 2 5<br/>
<br/>
link 5 6 2<br/>
<br/>
distance? 1 6<br/>
<br/>
distance? 2 3<br/>
<br/>
cut 2 4 3<br/>
<br/>
link 2 5 4<br/>
<br/>
distance? 4 1<br/>
<br/>
cut 4 6 3<br/>
<br/>
distance? 4 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">ok<br/>
<br/>
ok<br/>
<br/>
1 1<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
2 -1<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
failed<br/>
<br/>
failed<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
2 2<br/>
<br/>
3 3<br/>
<br/>
-1 -1<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
failed<br/>
<br/>
10 3<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
6 3<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
7 2<br/>
<br/>
ok<br/>
<br/>
7 2<br/>
<br/>
ok<br/>
<br/>
7 2<br/>
<br/>
ok<br/>
<br/>
-1 -1<br/>
<br/>
-1 -1<br/>
<br/>
ok<br/>
<br/>
3 3<br/>
<br/>
-1 -1<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
1 1<br/>
<br/>
-1 -1<br/>
<br/>
ok<br/>
<br/>
4 2<br/>
<br/>
5 1<br/>
<br/>
ok<br/>
<br/>
ok<br/>
<br/>
7 2<br/>
<br/>
ok<br/>
<br/>
-1 -1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
<br/><br/>
1 &lt;= n &lt;= 100000<br/><br/>
<br/><br/>
1 &lt;= m &lt;= 400000<br/><br/>
<br/><br/>
保证中间有关边权的计算不会超过int范围。（祝pascal选手早日转C++，其实我在说longint）<br/><br/>
<br/><br/>
<br/><br/>
<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By VFleaKing">By VFleaKing</a></p></div>

