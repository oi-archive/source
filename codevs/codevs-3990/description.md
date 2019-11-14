<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Skytree神犇最近在研究中国博大精深的数学。</p><p>这时，Sci蒟蒻前来拜访，于是Skytree给Sci蒟蒻出了一道数学题：</p><p>给定n个质数，以及k模这些质数的余数。问：在闭区间[a,b]中，有多少个k？最小的k是多少？</p><p>Sci蒟蒻数学能力差了Skytree几条街，所以他只好寻求计算机的帮助。他发邮件给同为oier的你，你能帮他解决这个问题吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为三个正整数n、a、b。</p><p>第2到n+1行，每行有两个整数，分别代表第n个质数和k模第n个质数的余数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出为两个整数，代表闭区间[a,b]中k的个数和闭区间[a,b]中最小的k。如果k不存在，则输出两个0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p><p>3 2 28</p><p>3 2</p><p>5 3</p><p>7 2</p><p>样例2：</p><p>3 24 31<br></p><p>3 2</p><p>5 3</p><p>7 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p><p>1</p><p>23<br></p><p>样例2：</p><p>0</p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=a&lt;=b&lt;=10^14</p><p>n&lt;=10</p><p>输入保证所有n个质数的乘积&lt;=10^14</p><p>每个质数&lt;=1.5*10^9</p><p>数据保证不会溢出64bit整数</p>
</div>
</div>