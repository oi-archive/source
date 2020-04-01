<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Problem有一个很长的由小写字母组成字符串。为了便于对这个字符串进行分析，需要将它划分成若干个部分，每个部分称为一个单词。出于减少分析量的目的，我们希望划分出的单词数越少越好。Output一个整数，表示字符串可以被划分成的最少的单词数。</p>
<ul>
<li>应该加上一个前提题目中提供的字符串肯定能被划分，否则输出增加判断语句。</li>
</ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 从文本文件word.in中读入数据。第一行，一个字符串。(字符串的长度不超过100)，第二行一个整数n，表示单词的个数。(n&lt;=100)，第3~n+2行，每行列出一个单词。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;一个整数，表示字符串可以被划分成的最少的单词数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>realityour<br>5<br>real<br>reality<br>it<br>your<br>our</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>(原字符串可拆成real+it+your或reality+our，由于reality+our仅为两个部分，因此最优解为2，另外注意，单词列表中的每个单词<span style="text-decoration: underline;">都可以重复使用多次，也可以不用</span>)</p>
</div>
</div>