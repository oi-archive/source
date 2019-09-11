# 题目描述


<h3>
【题目描述】
</h3>
<p>
Bi Luo是一名魔法少年，他有一棵魔法树，树有N个节点组成。每个节点上有一个价值为V[i]的宝藏，每条边有一个花费C[i]，代表每次经过这条边，都需要花费C[i]。
</p>
<p>
每个节点上的V[i]只会被取走一次，但如果你多次经过一条边，就要多次付出C[i]。
</p>
<p>
Bi Luo定义ans[i]为他从节点i开始走，最多能得到的价值（即宝藏减去花费）。
</p>
<p>
Bi Luo认为你们搞的这棵树啊，excited，因此他想要知道所有的ans[i]，你能帮助他吗？
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个正整数N。
</p>
<p>
接下来N行有N个正整数V[1..N]，其中1&lt;=V[i]&lt;=10^4.
</p>
<p>
接下来N-1行，每行三个正整数u,v,c，描述一条边，连接u,v，花费为c，其中1&lt;=c&lt;=10^4.
</p>
<h3>
【输出格式】
</h3>
<p>
输出N行，即ans[1..N]。
</p>
<h3>
【样例输入】
</h3>
<p>
5
</p>
<p>
4 1 7 7 7
</p>
<p>
1 2 6
</p>
<p>
1 3 1
</p>
<p>
2 4 8
</p>
<p>
3 5 2
</p>
<h3>
【样例输出】
</h3>
<p>
15
</p>
<p>
10
</p>
<p>
14
</p>
<p>
9
</p>
<p>
15
</p>
<h3>
【提示】
</h3>
<p>
N&lt;=10^5
</p>
<p>
V[i]&lt;=10^4
</p>
<p>
c&lt;=10^4
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://acm.hdu.edu.cn/contests/contest_showproblem.php?pid=1003&amp;cid=719" target="_blank">CCPC2016网络预选赛1003 Magic boy Bi Luo with his excited tree</a> 
</p>
