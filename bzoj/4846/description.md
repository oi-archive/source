
# Description

<div class="content"><div>对于一个变量x(-32768&lt;=x&lt;=32767)，给出一些约束条件，形如x &gt;= a,x &lt;= a</div>
<div>这些约束条件之间用||连接，然后你需要将这些约束条件简化，最后输出简化后的约束条件。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入不超过1000行，每行要么是两个用&amp;&amp;连接的约束条件，要么就是单个的约束条件</div>
<div>如果一行有两个约束条件，第一个约束条件总是x &gt;= a的形式，第二个约束总是x &lt;= a的形式。</div>
<div>除了输入的最后一行，每一行末尾都有一个||</div>
<div>并且所有的字符（除了&gt;=,&lt;=,&amp;&amp;,||）之间均由空格隔开，且没有多余的前置、后置空格。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，表示最简的约束条件的形式（也就是使输出的行数尽量少），其余格式与输入格式保持一致。</div>
<div>输出的若干行可以不按照特定的顺序输出。</div>
<div>特别地，如果对于任意的x∈[-32768,32767]，x均能满足约束条件，</div>
<div>仅输出一行true，反之，若对于任意的x∈[-32768,32767]，x均不能满足约束条件，仅输出一行false。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">x &gt;= 5 &amp;&amp; x &lt;= 10 ||<br/>
x &gt;= 7 &amp;&amp; x &lt;= 20 ||<br/>
x &lt;= 2 ||<br/>
x &gt;= 21 &amp;&amp; x &lt;= 25 ||<br/>
x &gt;= 8 &amp;&amp; x &lt;= 10 ||<br/>
x &gt;= 100</span></div>

# Sample Output

<div class="content"><span class="sampledata">x &lt;= 2 ||<br/>
x &gt;= 5 &amp;&amp; x &lt;= 25 ||<br/>
x &gt;= 100</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

