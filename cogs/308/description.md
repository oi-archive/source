# 题目描述


<h3>
【问题描述】
</h3>
<p>
有一个 $a\times b$ 的整数组成的矩阵，现请你从中找出一个 $n\times n$ 的正方形区域，使得该区域所有数中的最大值和最小值的差最小。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行为 $3$ 个整数，分别表示 $a,b,n$ 的值<br/>
第二行至第 $a+1$ 行每行为 $b$ 个非负整数，表示矩阵中相应位置上的数。每行相邻两数之间用一空格分隔。
</p>
<h3>
<b>【输出格式】</b> 
</h3>
<p>
仅一个整数，为 $a\times b$ 矩阵中所有“$n\times n$ 正方形区域中的最大整数和最小整数的差值”的最小值。
</p>
<h3>
【样例输入】
</h3>
<pre>5 4 2
1 2 5 6
0 17 16 0
16 17 2 1
2 10 2 1
1 2 2 2
</pre>
<h3>
【样例输出】
</h3>
<pre>1
</pre>
<h3>
【数据范围】
</h3>
<p>
（1）矩阵中的所有数都不超过 $1,000,000,000$。
</p>
<p>
（2）20% 的数据：$2\le a,b\le 100$，$n\le a,n\le b$，$n\le 10$。
</p>
<p>
（3）100% 的数据：$2\le a,b\le 1000$，$n\le a,n\le b$，$n\le 100$。
</p>