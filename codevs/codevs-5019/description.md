<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明读完了《<span style="font-family: Consolas, 'Lucida Console', monospace;">从一元一次方程到伽罗瓦理论</span>》，知道了一元五次及以上的更高次方程无根式解法，但他认为根式的精确解在实际生活中用途不大，而有用的则是如何求出高次方程的数值解。为此他沥尽心血研究出了一种算法以求一元五次方程的数值解。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共两行：</p><p>第一行为一元五次方程标准形式ax<sup>5</sup>+bx<sup>4</sup>+cx<sup>3</sup>+dx<sup>2</sup>+ex+f=0其中的系数a,b,c,d,e,f，用空格隔开；</p><p>第二行为需求精度n，即输出数值解的小数位数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出此方程中x给定精度的数值解。</p><p>若输入方程有不止一个实数解，输出其中最接近0的那一个。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例Ⅰ</p><p>1 1 1 1 1 1<br></p><p>4</p><p><span style="">╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲<span style="">╱</span><span style="">╲</span><span style="">╱</span><span style="">╲</span><span style="">╱</span><span style="">╲</span><span style="">╱</span><span style="">╲</span><span style="">╱</span><span style="">╲<span style="">╱</span><span style="">╲</span></span></span></p><p>样例Ⅱ</p><p>1 2 3 4 5 6<br></p><p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">样例Ⅰ</p><p style="">x=-1.0000<br></p><p style=""><span style="">╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲╱╲</span></p><p style="">样例Ⅱ</p><p>x=-1.49179799</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>a,b,c,d,e,f <span style="">＜</span> 2<sup>31</sup>, n <span style="">≤ <span style="">15.</span></span></p>
</div>
</div>