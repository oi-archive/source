# 题目描述


<h3>
【题目描述】
</h3>
<p>
给定一个整数序列 a[1],a[2],...,a[n]。
</p>
<p>
你需要支持如下三个操作：
</p>
<p>
加减操作：形如“A l r c”，表示将 a[l],a[l+1],...,a[r]都加上 c。
</p>
<p>
取最大操作：形如“M l r c”，表示将 a[l],a[l+1],...,a[r]都赋值为自己和 c 中较大的一个。
</p>
<p>
查询操作：形如“Q k”，表示求 a[k]的值，并且求从操作开始到该询问为止，a[k]的值变化的次数。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行为一个正整数 n。
</p>
<p>
第二行有 n 个整数，为序列 a[1],a[2],...,a[n]。
</p>
<p>
第三行为一个正整数 m，表示操作个数。
</p>
<p>
接下来 m 行，每行为一个操作，格式如上文所述
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个询问操作，输出一行两个整数，分别为 a[k]的值及变化次数。
</p>
<h3>
【样例输入】
</h3>
<pre>2
1 2
4
A 1 2 3
M 1 2 5
Q 1
Q 2
</pre>
<h3>
【样例输出】
</h3>
<pre>5 2
5 1
</pre>
<h3>
【提示】
</h3>
<p>
对于 30%的数据，满足 n,m≤10000。
</p>
<p>
对于另 30%的数据，保证操作中的数据均为随机生成。
</p>
<p>
对于 100%的数据，满足 1≤n,m≤100000，输入数据绝对值均小于 2^31。
</p>