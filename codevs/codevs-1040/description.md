<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个长度不超过200的由小写英文字母组成的字母串(约定;该字串以每行20个字母的方式输入，且保证每行一定为20个)。要求将此字母串分成k份(1&lt;k&lt;=40)，且每份中包含的单词个数加起来总数最大(每份中包含的单词可以部分重叠。当选用一个单词之后，其第一个字母不能再用。例如字符串this中可包含this和is，选用this之后就不能包含th)（管理员注：这里的不能再用指的是位置，不是字母本身。比如thisis可以算做包含2个is）。<br>单词在给出的一个不超过6个单词的字典中。<br>要求输出最大的个数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行为一个正整数(0&lt;n&lt;=5)表示有n组测试数据</span><br>每组的第一行有二个正整数(p，k)<br>p表示字串的行数;<br>k表示分为k个部分。<br>接下来的p行，每行均有20个字符。<br>再接下来有一个正整数s，表示字典中单词个数。(1&lt;=s&lt;=6)<br>接下来的s行，每行均有一个单词。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每行一个整数，分别对应每组测试数据的相应结果。</p>
<p><strong><br /></strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>1 3<br>thisisabookyouareaoh<br>4<br>is<br>a<br>ok<br>sab</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>this/isabookyoua/reaoh</p>
</div>
</div>