# 题目描述


<h3>
【题目描述】
</h3>
<p>
圣诞老人共有$M$个饼干，准备全部分给 $N$ 个孩子。每个孩子有一个贪婪度，第 $i$ 个孩子的贪婪度为 $g[i]$ 。如果有 $a[i]$ 个孩子拿到的饼干数比第$ i $个孩子多，那么第 $i$ 个孩子会产生 $g[i]*a[i]$ 的怨气。给定$N、M$和序列$g$，圣诞老人请你帮他安排一种分配方式，使得每个孩子至少分到一块饼干，并且所有孩子的怨气总和最小。$1≤N≤30, N≤M≤5000, 1&lt;=gi&lt;=10^7。$
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个整数N,M，第二行N个整数$g_1···g_N$。
</p>
<h3>
【输出格式】
</h3>
<p>
第一行一个整数表示答案，第二行N个整数表示每个孩子分到的饼干数。本题有SPJ，若有多种方案，输出任意一种均可。
</p>
<h3>
【样例输入】
</h3>
<pre>样例输入1:
3 20
1 2 3

样例输入2:
4 9
2 1 5 8
</pre>
<h3>
【样例输出】
</h3>
<pre>样例输出1
2
2 9 9

样例输出2
7
2 1 3 3
</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
《算法竞赛进阶指南》
</p>