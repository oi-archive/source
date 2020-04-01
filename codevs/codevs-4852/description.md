<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun;">蛇是由 <span style="font-family: TimesNewRomanPSMT;">n <span style="font-family: SimSun;">个点构成的折线<span style="font-family: TimesNewRomanPSMT;">(<span style="font-family: SimSun;">没有自交<span style="font-family: TimesNewRomanPSMT;">)<span style="font-family: SimSun;">。 初始时， 蛇的第 <span style="font-family: TimesNewRomanPSMT;">i <span style="font-family: SimSun;">个点在坐标<span style="font-family: TimesNewRomanPSMT;">(xi,yi)<span style="font-family: SimSun;">处， 蛇可以通过旋<br><span style="">转或者平移连续移动，但是它不能改变自己的形状。 <span style="font-family: TimesNewRomanPSMT;">y=0 <span style="font-family: SimSun;">这条直线是一堵墙，在坐标<span style="font-family: TimesNewRomanPSMT;">(0,0)<br><span style="font-family: SimSun;">处有一个小洞。问这个蛇能否从这个洞里通过<span style="font-family: TimesNewRomanPSMT;">(<span style="font-family: SimSun;">刚开始蛇身 <span style="font-family: TimesNewRomanPSMT;">y <span style="font-family: SimSun;">坐标大于 <span style="font-family: TimesNewRomanPSMT;">0<span style="font-family: SimSun;">，移动后蛇身 <span style="font-family: TimesNewRomanPSMT;">y <span style="font-family: SimSun;">坐<br><span style="">标均小于 <span style="font-family: TimesNewRomanPSMT;">0)<span style="font-family: SimSun;">？</span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">第一行包含一个 <span style="font-family: TimesNewRomanPSMT;">T<span style="font-family: SimSun;">，表示测试组数<span style="font-family: TimesNewRomanPSMT;">(T&lt;=5)<br><span style="font-family: SimSun;">每组测试数据首先输入一个 <span style="font-family: TimesNewRomanPSMT;">n<span style="font-family: SimSun;">，表示蛇节点数。<br><span style="">接下来 <span style="font-family: TimesNewRomanPSMT;">n <span style="font-family: SimSun;">行，第 <span style="font-family: TimesNewRomanPSMT;">i <span style="font-family: SimSun;">行两个数 <span style="font-family: TimesNewRomanPSMT;">xi,yi <span style="font-family: SimSun;">表示初始蛇第 <span style="font-family: TimesNewRomanPSMT;">i <span style="font-family: SimSun;">节点坐标<br><span style="">输入保证蛇不会自交并且没有重点，三点不共线。。</span></span></span><br style=""></span></span></span></span></span></span></span></span></span></span></span></span></span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun; font-size: 11pt;">输出 <span style="font-family: TimesNewRomanPSMT; font-size: 11pt;">T <span style="font-family: SimSun; font-size: 11pt;">行，如果蛇可以通过，输出 <span style="font-family: TimesNewRomanPSMT; font-size: 11pt;">Yes<span style="font-family: SimSun; font-size: 11pt;">，否则 <span style="font-family: TimesNewRomanPSMT; font-size: 11pt;">No<br style="orphans: 2; text-align: -webkit-auto; white-space: normal; widows: 2;"/></span></span></span></span></span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>4</p><p>0 1</p><p>1 1</p><p>1 2</p><p>2 2</p><p>11</p><p>63 106</p><p>87 143</p><p>102 132</p><p>115 169</p><p>74 145</p><p>41 177</p><p>56 130</p><p>28 141</p><p>19 124</p><p>0 156</p><p>22 183</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes</p><p>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">对于 <span style="font-family: TimesNewRomanPSMT;">50%<span style="font-family: SimSun;">的数据， <span style="font-family: TimesNewRomanPSMT;">1&lt;=n&lt;=10<br><span style="font-family: SimSun;">对于 <span style="font-family: TimesNewRomanPSMT;">100%<span style="font-family: SimSun;">的数据， <span style="font-family: TimesNewRomanPSMT;">1&lt;=n&lt;=1000<br><span style="">T&lt;=5,0&lt;=xi&lt;=1000000000,1&lt;=yi&lt;=1000000000</span></span><br style=""></span></span></span></span></span></span></span></p>
</div>
</div>