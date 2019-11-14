<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>作為创造產奶纪录的回报，Farmer John决定开始每个星期给Bessie一点零花钱。</p>
<p>FJ有一些硬币，一共有N (1 &lt;= N &lt;= 20)种不同的面额。每一个面额都能整除所有比它大的面额。</p>
<p>他想用给定的硬币的集合，每个星期至少给Bessie某个零花钱的数目C (1 &lt;= C &lt;= <br>100000000)。请帮他计算他最多能支付多少个星期的零花钱。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第一行: 两个由空格隔开的整数: N 和 C</p>
<p>* 第2到第N+1行: 每一行有两个整数表示一个面额的硬币：硬币面额V (1 &lt;= V &lt;= <br> 100,000,000)和Farmer John拥有的该面额的硬币数B (1 &lt;= B &lt;=<br> 1,000,000).</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>* 第一行: 一个单独的整数，表示Farmer John最多能给Bessie支付多少个星期至少為C的零用钱。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 6<br>10 1<br>1 100<br>5 120</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>111</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>FJ想要每个星期给Bessie六美分。他有100个1美分硬币，120个5美分硬币，和一个10美分硬币。</p>
<p>FJ可以在一个星期超额付给Bessie一个10美分硬币。然后接下来的10个星期每星期付给<br>Bessie两个5美分硬币。最后100个星期每星期付给Bessie一个1美分硬币跟一个5美分硬<br>币。</p>
<p> </p>
</div>
</div>