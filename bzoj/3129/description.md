
# Description

<div class="content"><p><span style="font-size: medium">给定方程<br/>
    X1+X2+. +Xn=M<br/>
我们对第l..N1个变量进行一些限制：<br/>
Xl &lt; = A<br/>
X2 &lt; = A2<br/>
Xn1 &lt; = An1<br/>
我们对第n1 + 1..n1+n2个变量进行一些限制：<br/>
Xn1+l &gt; = An1+1<br/>
Xn1+2 &gt; = An1+2<br/>
Xnl+n2 &gt; = Anl+n2<br/>
求：在满足这些限制的前提下，该方程正整数解的个数。<br/>
答案可能很大，请输出对p取模后的答案，也即答案除以p的余数。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">    输入含有多组数据，第一行两个正整数T，p。T表示这个测试点内的数据组数，p的含义见题目描述。<br/>
    对于每组数据，第一行四个非负整数n，n1，n2，m。<br/>
    第二行nl+n2个正整数，表示A1..n1+n2。请注意，如果n1+n2等于0，那么这一行会成为一个空行。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">  共T行，每行一个正整数表示取模后的答案。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 10007<br/>
3 1 1 6<br/>
3 3<br/>
3 0 0 5<br/>
<br/>
3  1  1  3<br/>
3  3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
6<br/>
0<br/>
<br/>
【样例说明】<br/>
对于第一组数据，三组解为(1，3，2)，(1,4,1),(2,3,1)<br/>
对于第二组数据，六组解为(1，1，3)，(1,2,2),(1,3,1),(2,1,2),(2,2,1),(3,1,1)<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">n &lt; = 10^9  , n1 &lt; = 8   , n2 &lt; = 8   ,  m &lt; = 10^9  ,p&lt;=437367875</span></p><br/>
<p><span style="font-size: medium">对于l00%的测试数据：  T &lt; = 5，1 &lt; = A1..n1_n2  &lt; = m，n1+n2 &lt; = n</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

