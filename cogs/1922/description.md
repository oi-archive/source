# 题目描述


<h3>
【题目描述】
</h3>
<p>
    对于欧洲人来说，“幸运数”是指那些十进制只由4或7组成的数。财务员Petya需要维护一个支持如下操作的整数数列：
</p>
<p>
    add l r d --- 表示将[l, r]区间内的所有数加上一个正整数d（$1 ≤ l ≤ r ≤ n, 1 ≤ d ≤ 10^4$）。
</p>
<p>
    count l r --- 统计[l, r]区间内有多少个“幸运数”。($1 \leq l, r \leq n$)
</p>
<p>
    请你帮助Petya实现它。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
    第一行有两个正整数n, m $(1 \leq n, m \leq 10^5)$，表示数组的长度和操作的个数。
</p>
<p>
    第二行有n个不大于$10^4$的正整数，表示这个初始数列。
</p>
<p>
    接下来有m行，每行表示一个操作。
</p>
<p>
    输入保证过程中数组中所有元素始终为不超过$10^4$的正整数.
</p>
<h3>
【输出格式】
</h3>
<p>
    输出若干行。对于所有的count l r 操作，按顺序给出每个询问的答案。
</p>
<h3>
【样例输入1】
</h3>
<pre><p>
3 6
2 3 4
count 1 3
count 1 2
add 1 3 2
count 1 3
add 2 3 3
count 1 3
</p>
</pre>
<h3>
【样例输出1】
</h3>
<pre><p>
1
0
1
1
</p>
</pre>
<h3>
</h3>
<h3>
【样例输入2】
</h3>
<pre><p>
4 5
4 4 4 4
count 1 4
add 1 4 3
count 1 4
add 2 3 40
count 1 4
</p>
</pre>
<h3>
【样例输出2】
</h3>
<pre><p>
4
4
4
</p>
</pre>
<br/>
<h3>
【来源】
</h3>
<p>
<a href="http://codeforces.com/problemset/problem/121/E" target="_blank">CF Round #91 (round#1 only) E</a> 
</p>
<p>
<br/>
</p>
