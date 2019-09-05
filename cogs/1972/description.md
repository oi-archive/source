# 题目描述


 【问题描述】<br/>
<p>
你突然有了一个大房子，房子里面有一些房间。事实上，你的房子可以看做是一个包含n*m个格子的格状矩形，每个格子是一个房间或者是一个柱子。在一开始的时候，相邻的格子之间都有墙隔着。
</p>
<p>
你想要打通一些相邻房间的墙，使得所有房间能够互相到达。在此过程中，你不能把房子给打穿，或者打通柱子（以及柱子旁边的墙）。同时，你不希望在房子中有小偷的时候会很难抓，所以你希望任意两个房间之间都只有一条通路。现在，你希望统计一共有多少种可行的方案。结果对10^9取余。
</p>
<p>
<br/>
</p>
<p>
【输入格式】
</p>
<p>
从room.in中读入。
</p>
<p>
第一行两个数分别表示n和m。
</p>
<p>
接下来n行，每行m个字符，每个字符都会是’.’或者’*’，其中’.’代表房间，’*’代表柱子。
</p>
<p>
<br/>
</p>
<p>
【输出格式】
</p>
<p>
输出到room.out中。
</p>
<p>
一行一个整数，表示合法的方案数。
</p>
<p>
<br/>
</p>
<p>
【样例输入1】
</p>
<p>
2
</p>
<p>
..
</p>
<p>
..
</p>
<p>
<br/>
</p>
<p>
【样例输出1】
</p>
<p>
4
</p>
<p>
<br/>
</p>
<p>
【样例输入2】
</p>
<p>
2
</p>
<p>
*.
</p>
<p>
.*
</p>
<p>
<br/>
</p>
<p>
【样例输出2】
</p>
<p>
0
</p>
<p>
<br/>
</p>
<p>
【数据规模与约定】
</p>
<p>
对于前20%的数据，n,m &lt;= 3
</p>
<p>
对于前50%的数据，n,m &lt;=5
</p>
<p>
对于前100%的数据，n,m&lt;=9
</p>
<p>
有40%的数据保证，min(n,m)&lt;=3
</p>
<p>
有30%的数据保证，不存在柱子
</p>