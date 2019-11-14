<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>定义一个对01串的压缩函数f：</p>
<p>    f(空串) = 空串。</p>
<p>    f(s) = s。 其中s是一个01串。</p>
<p>    f(s1, s2) = t, t是最短的满足s1是t的前缀且s2是t的后缀的01串。</p>
<p>        如f(001, 011) = 0011, f(111, 011) = 111011。</p>
<p>    f(a1, a2, …, an) = f( f(a1, a2, …, a[n-1]), an)</p>
<p>        如f(000, 000, 111) = f( f(000, 000), 111) = f(000, 111) = 000111</p>
<p>    对于给定的n个长度相等的01串a[1], a[2], …, a[n]，将其分为两个子序列b[1], b[2], …, b[k]和c[1], c[2], … , c[n-k]，使得</p>
<p>|f(b[1], b[2], … b[k])| + |f(c[1], c[2], … c[n-k])|最小化。</p>
<p>    不允许改变n个串之间的相对顺序，每个串属于且仅属于一个子序列，允许某个子序列为空。</p>
<p>    注：|s|表示01串s的串长度。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示01串的个数。</p>
<p>以下n行，每行m个0或1。第i+1行表示a[i]。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数m，表示|f(b[1], b[2], &hellip; b[k])| + |f(c[1], c[2], &hellip; c[n-k])|的最小值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>3</p>
<p>01</p>
<p>10</p>
<p>01</p>
<p>【样例输入2】</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>4</p>
<p>【样例输出2】</p>
<p>8</p>
<p> </p>
<p> </p>
<p>【样例解释】</p>
<p>    样例一：另一个子序列为空，则|f(01, 10, 01)| = |0101| = 4；</p>
<p>    样例二：b = {000, 001}， c = {111, 110}， |f(000, 001)| + |f(111, 110)| =|0001| + |1110| = 8;</p>
<p>体'&gt;4</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据， 1 &lt;= n &lt;= 10， 1 &lt;= m &lt;= 5；</p>
<p>对于另外20%的数据， m = 1；</p>
<p>对于60%的数据， 1 &lt;= n &lt;= 1000, 1 &lt;= m &lt;= 10</p>
<p>对于100%的数据， 1 &lt;= n &lt;= 2*10^5， 1 &lt;= m &lt;= 20；</p>
</div>
</div>