# 题目描述


<h3>
【题目描述】
</h3>
<p>
给定长度均为 $n$ 的数列 $a,b$，其中 $b$ 数列为 $[1,n]$ 的全排列，$a$ 数列全为 $0$。
</p>
<p>
你需要支持 $q$ 次操作，操作分为 $add$ 和 $query$ 两种。
</p>
<p>
$add\ l\ r$ 表示 $a_{l},a_{l+1},...,a_{r-1},a_r$均加 $1$。
</p>
<p>
$query\ l\ r$ 表示求 $\displaystyle\sum^r_{i=l}\lfloor\frac{a_i}{b_i}\rfloor$。
</p>
<p>
其中 $\lfloor x\rfloor$ 表示对 $x$ 下取整。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行有两个整数 $n,q$，$n$ 表示 $a,b$ 数列长度，$q$ 表示操作次数
</p>
<p>
接下来一行 $n$ 个整数，表示 $b$ 数列
</p>
<p>
接下来 $q$ 行，每行表示 $add$ 或 $query$ 操作
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一个 $query$ 操作，输出一行整数表示对应的答案
</p>
<h3>
【样例输入】
</h3>
<pre>5 12
1 5 2 4 3
add 1 4
query 1 4
add 2 5
query 2 5
add 3 5
query 1 5
add 2 4
query 1 4
add 2 5
query 2 5
add 2 2
query 1 5
</pre>
<h3>
【样例输出】
</h3>
<pre>1
1
2
4
4
6
</pre>
<h3>
【提示】
</h3>
<p>
对于100%的数据，$n,q\leq 100000,1\leq l,r\leq n$。
</p>
<p>
保证 $b$ 数列是 $[1,n]$ 的全排列
</p>
<h3>
【来源】
</h3>
<p>
2018多校训练-Naive Operations
</p>
