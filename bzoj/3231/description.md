
# Description

<div class="content"><div><span style="font-size: medium"><span style="color: #000020">一个由自然数组成的数列按下式定义：</span></span></div>
<div><span style="font-size: medium"><span style="color: #000020">对于</span><i><span style="color: #000020">i &lt;= k</span></i><i><span style="color: #000020">：</span></i><i><span style="color: #000020">a<sub>i</sub> = b<sub>i</sub></span></i></span></div>
<div><span style="font-size: medium"><span style="color: #000020">对于</span><i><span style="color: #000020">i &gt; k: a<sub>i</sub> = c<sub>1</sub>a<sub>i-1</sub> + c<sub>2</sub>a<sub>i-2</sub> + ... + c<sub>k</sub>a<sub>i-k</sub></span></i></span></div>
<div><span style="font-size: medium"><span style="color: #000020">其中</span><i><span style="color: #000020">b<sub>j</sub></span></i><span style="color: #000020">和</span><span style="color: #000020"> <i>c<sub>j</sub></i> </span><span style="color: #000020">（</span><i><span style="color: #000020">1&lt;=j&lt;=k</span></i><span style="color: #000020">）是给定的自然数。写一个程序，给定自然数</span><i><span style="color: #000020">m</span></i><span style="color: #000020"> &lt;= <i>n</i>, </span><span style="color: #000020">计算</span><i><span style="color: #000020">a<sub>m</sub></span></i><span style="color: #000020"> + <i>a<sub>m+1</sub></i> + <i>a<sub>m+2</sub></i> + ... + <i>a<sub>n</sub></i>, </span><span style="color: #000020">并输出它除以给定自然数</span><span style="color: #000020">p</span><span style="color: #000020">的余数的值。</span></span></div></div>

# Input

<div class="content"><div><span style="font-size: medium"><span style="color: #000020">由四行组成。</span></span></div>
<div><span style="font-size: medium"><span style="color: #000020">第一行是一个自然数</span><i><span style="color: #000020">k</span></i><span style="color: #000020">。</span></span></div>
<div><span style="font-size: medium"><span style="color: #000020">第二行包含</span><i><span style="color: #000020">k</span></i><span style="color: #000020">个自然数</span><i><span style="color: #000020">b<sub>1</sub>, b<sub>2</sub>,...,b<sub>k</sub></span></i><span style="color: #000020">。</span></span></div>
<div><span style="font-size: medium"><span style="color: #000020">第三行包含</span><i><span style="color: #000020">k</span></i><span style="color: #000020">个自然数</span><i><span style="color: #000020">c<sub>1</sub>, c<sub>2</sub>,...,c<sub>k</sub></span></i><span style="color: #000020">。</span></span></div>
<div><span style="font-size: medium"><span style="color: #000020">第四行包含三个自然数</span><i><span style="color: #000020">m</span></i><span style="color: #000020">, <i>n</i>, <i>p</i></span><span style="color: #000020">。</span></span></div></div>

# Output

<div class="content"><div><span style="font-size: medium"><span style="color: #000020">仅包含一行：一个正整数，表示</span><span style="color: #000020">(<i>a<sub>m</sub></i> + <i>a<sub>m+1</sub></i> + <i>a<sub>m+2</sub></i> + ... + <i>a<sub>n</sub></i>) mod <i>p</i></span><span style="color: #000020">的值。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 1<br/>
1 1<br/>
2 10 1000003<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">142</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
对于100%的测试数据：<br/><br/>
1&lt;= k&lt;=15<br/><br/>
1 &lt;= m &lt;= n &lt;= 1018<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

