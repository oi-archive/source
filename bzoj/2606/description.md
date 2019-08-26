
# Description

<div class="content"><div><span style="font-size: medium">我们考虑一个字符序列. 如果 <i>x</i><sub>1</sub><i>x</i><sub>2</sub>...<i>x<sub>n</sub></i> 包含一个<em>stammer</em>, 当且仅当我们能在里面找到两个相同的连续的子串。即存在<i>i</i> 和 <i>j</i> (1 &lt;= <i>i</i> &lt; <i>j</i> &lt;= (<i>n</i>+<i>i</i>+1)/2) ，其中 <i>x<sub>i</sub></i> = <i>x<sub>j</sub></i>, <i>x<sub>i</sub></i><sub>+1</sub> = <i>x<sub>j</sub></i><sub>+1</sub>, ..., <i>x<sub>j</sub></i><sub>-1</sub> = <i>x</i><sub>2<i>j</i>-<i>i</i>-1</sub>. </span></div>
<div><span style="font-size: medium">我们想找出一个长度为<i>n</i>的序列其中不含stammers, 请构造一个这样的序列并使用最少的关键字. </span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>Example</b></span></div>
<div><span style="font-size: medium">当<i>n</i> = 3 只需要使用两个字母<i>a</i> 和 <i>b</i> 即可: <i>aba</i> and <i>bab</i>. 当 <i>n</i> = 5 时我们需要3个字母，一个例子为：<i>abcab</i> 是一个合法的串。 </span></div>
<p></p></div>

# Input

<div class="content"><p></p>
<div><span style="font-size: medium">只有一行仅有一个数表示<i>n</i>, 1 &lt;= <i>n</i> &lt;= 10000000.</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">第一行仅输出一个数，代表使用的关键字种类，然后接下来一行<i>n</i> 个小写字符表示构造出的合法串.</span></div>
<div><span style="font-size: medium">你可以假设26个小写字母是足够可用的。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

