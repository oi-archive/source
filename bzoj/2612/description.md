
# Description

<div class="content"><div><span style="font-size: medium">我们给定一个整数集合<i>A</i>. 考虑一个非负整数集合<i>A</i>&#39;, 所有属于<i>A</i>&#39; 的集合的数x满足当且仅当能被表示成一些属于<i>A</i> 的元素的和(数字可重复). 比如, 当 <i>A</i> = {2,5,7}, 属于<i>A</i>&#39; 的数为: 0 (0个元素的和), 2, 4 (2  +  2) and 12 (5 + 7 or 7 + 5 or 2 + 2 + 2 + 2 + 2 + 2); 但是元素1和3不属于<i>A</i>&#39;.</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行有一个整数<i>n</i>: 代表集合 <i>A</i>的元素个数, 1 &lt;= <i>n</i> &lt;= 5000. 接下来每行一个数<i>a<sub>i</sub></i>描述一个元素, 1 &lt;= <i>a<sub>i</sub></i> &lt;= 50000. <i>A</i> = {<i>a</i><sub>1</sub>, <i>a</i><sub>2</sub>, ..., <i>a<sub>n</sub></i>}, <i>a</i><sub>1</sub> &lt; <i>a</i><sub>2</sub> &lt; ... &lt; <i>a<sub>n</sub></i>. </span></div>
<div><span style="font-size: medium">接下来一个整数<i>k</i>, 1 &lt;= <i>k</i> &lt;= 10000. 每行一个0 到 1000000000, 分别代表<i>b</i><sub>1</sub>, <i>b</i><sub>2</sub>, ..., <i>b<sub>k</sub></i>.</span></div>
<div></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出<i>k</i>行. 第<i>i</i>行打印<tt>TAK</tt>, 如果 <i>b<sub>i</sub></i> 属于<i>A</i>&#39;, 否则打印<tt>NIE</tt>. </span></div>
<p><divre></divre>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
<br/>
2<br/>
5<br/>
7<br/>
6<br/>
0<br/>
1<br/>
4<br/>
12<br/>
3<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE<br/>
TAK<br/>
TAK<br/>
NIE<br/>
TAK<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

