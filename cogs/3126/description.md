# 题目描述


<h3>
【题目描述】
</h3>
<p>
   给定一个自然数$N$，要求把$N$拆分成若干个正整数相加的形式，参与加法运算的数可以重复。求拆分的方案数 mod 2147483648的结果。$1≤N≤4000$。
</p>
<h3>
【输入格式】
</h3>
<p>
一个整数$N$。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个数，即所有方案数
</p>
<p>
因为这个数可能非常大，所以你只要输出这个数 mod 2147483648 的余数即可。
</p>
<h3>
【样例输入】
</h3>
<pre>7</pre>
<h3>
【样例输出】
</h3>
<pre>14</pre>
<h3>
【提示】
</h3>
<p>
输入7，则7拆分的结果是
</p>
<p>
7=1+6
</p>
<p>
7=1+1+5
</p>
<p>
7=1+1+1+4
</p>
<p>
7=1+1+1+1+3
</p>
<p>
7=1+1+1+1+1+2
</p>
<p>
7=1+1+1+1+1+1+1
</p>
<p>
7=1+1+1+2+2
</p>
<p>
7=1+1+2+3
</p>
<p>
7=1+2+4
</p>
<p>
7=1+2+2+2
</p>
<p>
7=1+3+3
</p>
<p>
7=2+5
</p>
<p>
7=2+2+3
</p>
<p>
7=3+4
</p>
<p>
一共有14种情况，所以输出14 mod 2147483648，即14
</p>
<h3>
【来源】
</h3>
<p>
《算法竞赛进阶指南》
</p>