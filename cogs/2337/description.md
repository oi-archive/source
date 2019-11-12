# 题目描述


<h3>
【问题描述】
</h3>
<p class="MsoNormal" style="text-align:left;" align="left">
给出 $n$ 个数 $q_i$，给出 $F_j$ 的定义如下：
</p>
<p class="MsoNormal" style="text-align:left;" align="left">
$$F_j=\sum_{i&lt;j}\frac{q_iq_j}{(i-j)^2}-\sum_{i&gt;j}\frac{q_iq_j}{(i-j)^2}$$
</p>
<p class="MsoNormal" style="text-align:left;" align="left">
令 $E_i=\frac{F_i}{q_i}$，求 $E_i$.
</p>
<h3>
【输入格式】
</h3>
<p>
包含一个整数 $n$，接下来 $n$ 行每行输入一个数，第 $i$ 行表示 $q_i$。
</p>
<h3>
【输出格式】
</h3>
<p>
有 $n$ 行，第 $i$ 行输出 $E_i$。与标准答案误差不超过 $10^{-2}$即可。
</p>
<h3>
【样例输入】
</h3>
<pre>5
4006373.885184
15375036.435759
1717456.469144
8514941.004912
1410681.345880
</pre>
<h3>
【样例输出】
</h3>
<pre>-16838672.693
3439.793
7509018.566
4595686.886
10903040.872
</pre>
<h3>
【数据规模与约定】
</h3>
<p>
对于 30% 的数据，$n\le 1000$。
</p>
<p>
对于 50% 的数据，$n\le 60000$。
</p>
<p>
对于 100% 的数据，$n\le 100000$。<qi<1000000000。< p=""></qi<1000000000。<>
</p>
