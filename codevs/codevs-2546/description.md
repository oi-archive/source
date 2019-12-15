<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<pre>     你和你的朋友玩一个游戏。你的朋友写下来一连串的0或者1。你选择一个连续的子序列然后问他，这个子序列包含1的个数是</pre>
<pre>奇数还是偶数。你的朋友回答完你的问题，接着你问下一个问题。</pre>
<pre>     你怀疑你朋友的一些答案可能是错误的，你决定写一个程序来帮忙。程序将接受一系列你的问题及你朋友的回答，程序的目的</pre>
<pre>是找到第一个错误的回答i，也就是存在一个序列满足前i-1个问题的答案，但是不满足前i个问题。</pre>
<pre> </pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<pre>第一行有一个整数<span>L</span>（<span>L&lt;=1000000000</span>）<span>,</span>是这个<span>01</span>序列的长度。第二行是一个整数<span>N(N&lt;=5000),</span>是问题及其答案的数目<span>,</span></pre>
<pre>接下来<span>N</span>行描述问题和答案。每一行包含一个问题和这个问题的答案：</pre>
<pre>两个整数（子序列的起始位置和结束位置）和一个单词‘<span>even</span>’或者‘<span>odd</span>’<span>,</span></pre>
<pre>‘<span>even</span>’表示这个子序列中的‘<span>1</span>’的个数是偶数，</pre>
<pre>‘<span>odd</span>’则表示是奇数。</pre>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<pre><span style="font-family: 宋体; font-size: small;">只需输出一行一个整数X。</span></pre>
<pre><span style="font-family: 宋体; font-size: small;">表示存在一个01序列满足前面的X个问题，但是不存在一个01序列满足前X+1个问题，如果存在一个序列满足所有问题，</span></pre>
<pre><span style="font-family: 宋体; font-size: small;">则输出N。</span></pre>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>              10</pre>
<pre>               5</pre>
<pre>               1 2 even</pre>
<pre>               3 4 odd</pre>
<pre>               5 6 even</pre>
<pre>               1 6 even</pre>
<pre>               7 10 odd</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>  </p>
</div>
</div>