<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>直线上有 n 颗行星，x=i 处有行星 i。行星 j 受到行星 i 的作用力，当且仅当i&lt;=αj，此时 j 受作用力的大小为： <br>Fij=mi*mj/(j-i)</p>
<p>其中α为很小的常量，故直观上说，每颗行星都只受距离遥远的行星的作用。请计算每颗行星的受力。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n和α， 1&lt;=n&lt;=10<sup>5</sup>， 1&lt;α&lt;=3.5，接下来n行输入n个行星的质量mi，保证0&lt;=mi&lt;=10<sup>7</sup>.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>n行，依次输出各行星的受力情况。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 0.3 <br>3 <br>5 <br>6 <br>2 <br>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.000000 <br>0.000000 <br>0.000000 <br>1.968750 <br>2.976000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=10<sup>5</sup></p>
</div>
</div>