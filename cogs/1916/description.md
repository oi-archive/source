# 题目描述


<h3>
【题目描述】
</h3>
<p>
    对于两个长度均为N的字符串s, t，定义：
</p>
<p>
    $h(s, t)$为两个字符串中字符相同的位置个数,
</p>
<p>
    <img src="http://espresso.codeforces.com/3185549447bcef14eee362fe5c14adf50d614ba9.png" alt=""/> 
</p>
<p>
    其中$shift(s, i)$表示将字符串s循环左移得到的字符串。
</p>
<p>
    例如：ρ(&#34;AGC&#34;, &#34;CGT&#34;) =  h(&#34;AGC&#34;, &#34;CGT&#34;) + h(&#34;AGC&#34;, &#34;GTC&#34;) + h(&#34;AGC&#34;, &#34;TCG&#34;) +  h(&#34;GCA&#34;, &#34;CGT&#34;) + h(&#34;GCA&#34;, &#34;GTC&#34;) + h(&#34;GCA&#34;, &#34;TCG&#34;) +  h(&#34;CAG&#34;, &#34;CGT&#34;) + h(&#34;CAG&#34;, &#34;GTC&#34;) + h(&#34;CAG&#34;, &#34;TCG&#34;) =  1 + 1 + 0 + 0 + 1 + 1 + 1 + 0 + 1 = 6.
</p>
<p>
    现在，你有一个长度为N 的DNA串S。你希望求出所有使得$\rho(S, T)$取最大值的DNA串T 的个数。换句话说，你要求出满足<img src="http://espresso.codeforces.com/8689349142c7afec51741bca879d960cce9678c8.png" alt=""/>的长度为N 的DNA串T 的个数。其中DNA串表示所有字符均为A,G,C,T的字符串。
</p>
<p>
    由于这个答案可能很大，你只需输出这个数除以$10^9 + 7$的余数。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行是一个正整数N，表示DNA串的长度。
</p>
<p>
第二行是一个长度为N 的DNA串S。
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个整数。
</p>
<h3>
【样例输入1】
</h3>
<pre>1
C
</pre>
<h3>
【样例输出1】
</h3>
<pre>1</pre>
<h3>
【样例输入2】
</h3>
<pre>2
CG
</pre>
<h3>
【样例输出2】
</h3>
<pre>4</pre>
<h3>
【样例输入3】
</h3>
<pre>3
TTT
</pre>
<h3>
【样例输出3】
</h3>
<pre>1</pre>
<h3>
【数据范围与提示】
</h3>
<p>
$1 \leq N \leq 10^5$
</p>
<p>
字符串中只包含A,G,C,T.
</p>
<p>
NOTE：
</p>
<p>
    
</p>
<p>
Please note that if for two distinct strings t1 and t2 values ρ(s, t1) и ρ(s, t2) are maximum among all possible t,
</p>
<p>
then both strings must be taken into account in the answer even if one
</p>
<p>
of them can be obtained by a circular shift of another one.
</p>
<p>
In the first sample, there is ρ(&#34;C&#34;, &#34;C&#34;) = 1, for the remaining strings t of length 1 the value of ρ(s, t) is 0.
</p>
<p>
In the second sample, ρ(&#34;AG&#34;, &#34;AG&#34;) = ρ(&#34;AG&#34;, &#34;GA&#34;) = ρ(&#34;AG&#34;, &#34;AA&#34;) = ρ(&#34;AG&#34;, &#34;GG&#34;) = 4.
</p>
<p>
In the third sample, ρ(&#34;TTT&#34;, &#34;TTT&#34;) = 27
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
CF #295 div1 A
</p>
