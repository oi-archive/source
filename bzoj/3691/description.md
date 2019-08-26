
# Description

<div class="content"><p><span style="font-size: medium">每年春季，在某岛屿上都会举行游行活动。<br/>
在这个岛屿上有N个城市，M条连接着城市的有向道路。<br/>
你要安排英雄们的巡游。英雄从城市si出发，经过若干个城市，到城市ti结束，需要特别注意的是，每个英雄的巡游的si可以和ti相同，但是必须至少途径2个城市。<br/>
每次游行你的花费将由3部分构成：<br/>
1.每个英雄游行经过的距离之和，需要特别注意的是，假如一条边被途径了k次，那么它对答案的贡献是k*ci，ci表示这条边的边权。<br/>
2.如果一个英雄的巡游的si不等于ti，那么会额外增加C的费用。因为英雄要打的回到起点。<br/>
3.如果一个城市没有任何一个英雄途经，那么这个城市会很不高兴，需要C费用的补偿。<br/>
你有无数个的英雄。你要合理安排游行方案，使得费用最小。<br/>
由于每年，C值都是不一样的。所以你要回答Q个询问，每个询问都是，当C为当前输入数值的时候的答案。</span></p></div>

# Input

<div class="content"><p><font size="4">第一行正整数N，M，Q；<br/>
接下来的M行，每行ai,bi,ci，表示有一条从ai到bi，边权为ci的有向道路。保证不会有自环，但不保证没有重边。<br/>
接下来Q行，每行一个C，表示询问当每次费用为C时的最小答案。</font></p></div>

# Output

<div class="content"><p><font size="4">Q行，每行代表一个询问的答案。</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 5 3<br/>
1 3 2<br/>
2 3 2<br/>
3 4 2<br/>
4 5 2<br/>
4 6 2<br/>
1<br/>
5<br/>
10 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
21<br/>
32<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【样例说明】<br/><br/>
第一年的时候，C只有1。我们比较懒所以就不安排英雄出游了，需要支付6的费用。<br/><br/>
第二年的时候，我们可以这么安排：<br/><br/>
第一个英雄1-&gt;3-&gt;4-&gt;5，需要付2+2+2=6的费用，同时还要花5费用打的回家。再花5+5的费用来补偿2号城市和6号城市。<br/><br/>
第三年略。</span></p><br/>
<p><span style="font-size: medium">【数据范围】<br/><br/>
对于100%的数据，2&lt;=N&lt;=250,1&lt;=M&lt;=30000,1&lt;=Q&lt;=10000。<br/><br/>
1&lt;=ci&lt;=10000,1&lt;=C&lt;=10000。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

