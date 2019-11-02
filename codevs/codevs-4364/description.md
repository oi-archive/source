<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><br></span></p><p style=""><span style="">再过两天就是<span style="font-family: Times New Roman;">Eli</span><span style="">酱的生日了，μ</span></span><span style="">’</span><span style="">s<span style="">的大家都会给</span><span style="font-family: Times New Roman;">Eli</span><span style="">酱送生日礼物。</span><span style="font-family: Times New Roman;">Kotori</span><span style="">知道</span><span style="font-family: Times New Roman;">Eli</span><span style="">十分喜欢吃</span><span style="font-family: Times New Roman;">chocolate</span><span style="">，于是便决定送给</span><span style="font-family: Times New Roman;">Eli</span><span style="">两个可以制造</span><span style="font-family: Times New Roman;">chocolate</span><span style="">的魔法小鸟。这两只小鸟会按照预先告知的指示进行飞行，指示包括</span><span style="font-family: Times New Roman;">N,S,E,W</span><span style="">四个指示，分别对应北，南，东，西四个方向，执行某个指示时，小鸟会按照各自的指示飞行一个单位，而每秒会有一个指示。</span></span></p><p style=""><span style="">两只小鸟最后所在的位置与起始位置围成的图形面积就是能生成的chocolate量。作为魔法小鸟，它自然会在<span style="font-family: Times New Roman;">Eli</span><span style="">希望的时间内循环执行给定的指示（执行完指示串后它会从头开始循环）。在</span><span style="font-family: Times New Roman;">0</span><span style="">时刻</span><span style="font-family: Times New Roman;">Eli</span><span style="">酱会将两只魔法小鸟放在（</span><span style="font-family: Times New Roman;">x,y</span><span style="">）位置，并且给出了指示串。她想知道最后能生成的</span><span style="font-family: Times New Roman;">chocolate</span><span style="">量。</span></span></p><p style=""><span style=""><span style="font-family: Times New Roman;"></span></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行：两个整数<span style="font-family: Times New Roman;">x</span><span style="">、</span><span style="font-family: Times New Roman;">y</span><span style="">，表示两只小鸟的初始位置</span><span style="font-family: Times New Roman;">(x,y)</span></span></p><p style=""><span style="">第二、</span><span style="">三行：两个指示串，分别表示对两只小鸟的指示</span></p><p style=""><span style="">第四行：两个整数<span style="font-family: Times New Roman;">T1,T2</span><span style="">，分别表示两只小鸟的飞行时间</span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:14px">一个数，保留<span style="font-family:Times New Roman">4</span><span style="font-family:宋体">位小数，表示生成的巧克力量。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2 2</span></p><p style=""><span style="">NNNNNEEEEE</span></p><p style=""><span style="">NNNNN</span></p><p style=""><span style="">10 5</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">12.5000</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于<span style="font-family: Times New Roman;">60</span><span style="">％的数据：</span><span style="font-family: Times New Roman;">T1,T2</span><span style="">≤</span><span style="font-family: Times New Roman;">500000</span><span style="">且指示串长度≤</span><span style="font-family: Times New Roman;">500000</span></span></p><p style=""><span style="">对于<span style="font-family: Times New Roman;">100</span><span style="">％的数据：</span><span style="font-family: Times New Roman;">T1,T2&lt;=100000000</span><span style="">且指示串长度≤</span><span style="font-family: Times New Roman;">500000</span><span style="">，</span><span style="font-family: Times New Roman;">|x|,|y|</span><span style="">≤</span><span style="font-family: Times New Roman;">100000000</span></span></p><p><br></p>
</div>
</div>