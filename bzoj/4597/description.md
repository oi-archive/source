
# Description

<div class="content"><div>
<div>
<div>你的面前有N个数排成一行。分别为A1, A2, … , An。你打算在每相邻的两个 Ai和 Ai+1 间都插入一个加号或者</div>
<div>减号或者乘号。那么一共有 3^(n-1) 种可能的表达式。你对所有可能的表达式的值的和非常感兴趣。但这毕竟太</div>
<div>简单了，所以你还打算支持一个修改操作，可以修改某个Ai 的值。你能够编写一个程序对每个修改都输出修改完</div>
<div>之后所有可能表达式的和吗？注意，修改是永久的，也就是说每次修改都是在上一次修改的基础上进行， 而不是</div>
<div>在最初的表达式上进行。</div>
</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含 2 个正整数 N 和 Q，为数的个数和询问的个数。</div>
<div>接下来一行 n 个非负整数，依次表示a1,a2...an</div>
<div>在接下来 Q 行，其中第 ?? 行两个非负整数Ti 和Vi，表示要将 A<sub>ti</sub> 修改为 Vi。其中 1 ≤ Ti ≤ N。</div>
<div>保证对于 1 ≤ J ≤ N, 1 ≤ i≤ Q，都有 Aj,Vi ≤ 10^4。</div>
<div>N,Q&lt;=100000,本题仅有三组数据</div>
<p></p></div>

# Output

<div class="content"><div>输出共 Q 行，其中第 i 行表示第 i 个询问之后所有可能表达式的和，对10^9 + 7 取模。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
9384 887 2778 6916 7794<br/>
2 8336<br/>
5 493<br/>
3 1422<br/>
1 28<br/>
4 60<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">890543652<br/>
252923708<br/>
942282590<br/>
228728040<br/>
608998099</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

