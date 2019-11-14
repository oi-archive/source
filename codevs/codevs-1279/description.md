<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>在那楼梯那边数实里面，有一只 guard，他活泼又聪明，他卖萌又霸气。他每天刷题虐 场 D 人考上了 PKU，如果无聊就去数一数质数~~ 有一天 guard 在纸上写下了一串数字，他发现数出每个数有多少个质因子是非常有(wu) 趣(liao)的事情，于是快乐的开始了数质因子之旅。现在他有一个更有(wu)趣(liao)的想法， 他想知道第a个数到第b个数每个数的质因子个数之和。更有趣的是，他一共写下了200 万个数字哟。由于guard是神犇所以不屑于求如此简单的问题，现在他把问题交给了Mr.shu， 但是他不会…，如果你能回答他的问题就能获得 guard 的亲笔签名哦~~。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行 1 个数 n，表示 guard 写下了 n 个数。 第二行 n 个用空格隔开的数，表示 guard 写下的 n 个数(每个数都不大于 10000，不小 于 1)。 第三行 1 个数 m，表示 guard 的询问数。 接下来 m 行，每行一个 a 和 b，表示 guard 想知道 a 到 b（包括 a 和 b）的每个数的质 因子个数之和。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一共 m 行。每行一个数表示对每个询问的答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5
4 2 1 6 30
2
1 3
2 5 </pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>3
6</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span><span>【输入输出样例说明】</span></span></p>
<p> </p>
<p><span><span>4=2*2 有 2 个不同质因子，2 有 1 个，1 有 0 个，6 有 2 个，30 有 3 个，</span></span></p>
<p> </p>
<p><span><span>所以[1,3]有 2+1+0 个，[2,5]有 1+0+2+3 个。</span></span></p>
<p> </p>
<p><span><span>【数据范围】</span></span></p>
<p> </p>
<p><span><span>20%的数据满足 n&lt;=1000,m&lt;=10</span></span></p>
<p> </p>
<p><span><span>50%的数据满足 n&lt;=10000</span></span></p>
<p> </p>
<p><span><span>100%的数据满足 n&lt;=2000000，m&lt;=100000</span></span></p>
</div>
</div>