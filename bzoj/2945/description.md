
# Description

<div class="content"><div><span style="font-size: medium">在一个气垫船厂用不同高度方块建造了一个测试轨道。一条完美的轨道，被称做<b>lollobrigida</b>，是相邻两个方块的高度不同且连续的三个方块的高度既不是递减也不是递增的轨道。</span></div>
<div><span style="font-size: medium">用更形式的表达，设<i>h<sub>1</sub>,...,h<sub>n</sub></i>是建造轨道的方块的高度。如果任意1 &lt;= <i>i</i> &lt;= <i>n</i>-2都有满足下面条件：</span></div>
<ul type="disc">
    <li><span style="font-size: medium"><i>h<sub>i</sub></i> &lt; <i>h<sub>i+1</sub></i> and <i>h<sub>i+1</sub></i> &gt; <i>h<sub>i+2</sub></i> or </span></li>
    <li><span style="font-size: medium"><i>h<sub>i</sub></i> &gt; <i>h<sub>i+1</sub></i> and <i>h<sub>i+1</sub></i> &lt; <i>h<sub>i+2</sub></i>, </span></li>
</ul>
<div><span style="font-size: medium">这样我们便称一条轨道为<b>lollobrigida</b>。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>例子</b></span></div>
<div><span style="font-size: medium">我们不可能用下面一组高度的方块来建造lollobrigida：3, 3, 3, 5, 2，因为两个高度为3的方块会相邻或者会出现下列情况：(2,3,5)或者(5,3,2)，这些都是不允许的。</span></div>
<div><span style="font-size: medium">这儿有一个用另一组高度的方块建造的lollobrigida的例子(3, 2, 5, 2, 3, 1)。 我们也可以用这些方块建造其他不同的lollobrigidas。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>任务</b></span></div>
<div><span style="font-size: medium">读入几组数据，对于每一组数据：</span></div>
<ul type="disc">
    <li><span style="font-size: medium">读入方块的个数和每个方块的高度</span></li>
    <li><span style="font-size: medium">检查是否能建造lollobrigida</span></li>
</ul></div>

# Input

<div class="content"><div style="margin: auto 0cm"><span style="font-size: medium">第一行有一个正整数d，1 &lt;= <i>d</i> &lt;= 100，表示输入数据的组数。接下来的一行是第一组数据。</span></div>
<div><span style="font-size: medium">在每组数据的第一行有一个正整数n，3 &lt;= <i>n</i> &lt;= 1000000，表示方块的个数。</span></div>
<div><span style="font-size: medium">接下来的<i>n</i>行中每行有一个正整数<i>h</i> 表示一个方块的高度1 &lt;= <i>h</i> &lt;= 10<sup>9</sup>。</span></div>
<div><span style="font-size: medium">接着是下一组数据。</span></div></div>

# Output

<div class="content"><div style="margin: auto 0cm"> </div>
<div><span style="font-size: medium">应该有<i>d</i>行，一个表示一组数据。每一行都有一个单词，第<i>i</i> 行的单词：</span></div>
<ul type="disc">
    <li><span style="font-size: medium">TAK (波兰语中是的意思)，如果第<i>i</i>组数据可以建造lollobrigida</span></li>
    <li><span style="font-size: medium">NIE (波兰语中否的意思)，不可以建造</span></li>
</ul></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5<br/>
3<br/>
3<br/>
3<br/>
5<br/>
2<br/>
6<br/>
3<br/>
3<br/>
1<br/>
5<br/>
2<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NIE<br/>
TAK<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

