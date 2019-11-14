<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      递变是指通过增加、减少或改变单词x中的一个字母，使它变成字典中的另一个单词y。比如将dig变成dog，将dog变成do都是递变。递变阶梯是一个按字典序排列的单词序列w<sub>1</sub>,w<sub>2</sub>,...w<sub>n</sub>，满足对于从1到n-1的所有i，单词w<sub>i</sub>到w<sub>i+1</sub>都是一次递变。相同的单词之间不能递变。</p>
<p>      给出一部字典，你要计算其中最长的递变阶梯。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一部字典：每行都是一个由小写字母构成的单词。所有单词按照字典序排列。</p>
<p>所有的单词长度都不超过16，且字典中最多有15000个单词。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示最长的递变阶梯包含的单词数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>cat</p>
<p>dig</p>
<p>dog</p>
<p>fig</p>
<p>fin</p>
<p>fine</p>
<p>fog</p>
<p>log</p>
<p>wine</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证字典中的单词数量不超过1000</p>
<p>对于100%的数据，保证字典中的单词数量不超过15000</p>
</div>
</div>