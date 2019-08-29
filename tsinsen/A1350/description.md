<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　你得到了一个由 N 个非负整数构成的序列 A。<br/>
　　你需要回答关于这个序列的 Q 次询问。<br/>
　　每次询问将提供三个整数参数 v,a,b。你需要统计满足以下三个条件的整数<br/>
　　数对(i, j)的数目:1 &lt;= i &lt;= j &lt;= N, a &lt;= j-i+1 &lt;= b, 并且对于任意i &lt;= k &lt;= j的整数k有A[k] &gt;= v。其中A[k]表示序列A的第k项。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包括两个正整数 N, Q,分别表示序列 A 的项数和询问数。 第二行,N 个非负整数。其中第 i 个整数表示 A[i]。<br/>
　　接下来的 Q 行,每行 3 个整数 v, a, b,依次表示一次询问的三个参数。</div>
# 输出格式

<div class="pdcont">　　输出 Q 行,每行一个非负整数。第 i 行的非负整数表示第 i 次询问 的答案。</div>
# 样例输入

<div class="pddata">5 3<br/>
5 3 2 7 4<br/>
3 2 3<br/>
2 2 5<br/>
4 1 1</div>
# 样例输出

<div class="pddata">2<br/>
10<br/>
3</div>
# 数据规模和约定

<div class="pdcont">　　20%的数据满足,1 &lt;= N &lt;= 1 000, 1 &lt;= Q &lt;= 1 000;<br/>
　　40%的数据满足,1 &lt;= N &lt;= 50 000, 1 &lt;= Q &lt;= 50 000;<br/>
　　60%的数据满足,1 &lt;= N &lt;= 100 000, 1 &lt;= Q &lt;= 100 000; 100%的数据满足,1 &lt;= N &lt;= 300 000, 1 &lt;= Q &lt;= 300 000, 0 &lt;= A[i], v &lt;= 1 000, 1 &lt;= a, b &lt;= 200 000.</div>

</div>