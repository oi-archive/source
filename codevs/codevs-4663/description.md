<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">zed<span style="">最近总是受到</span>Farmer<span style="">的困扰，因此他在自家的门前插了一排栅栏以防农气的入侵。栅栏由</span>N<span style="">个竖条栅栏横向组成，每个竖条栅栏宽度为</span>1<span style="">。</span></p><p style=""><span style="">过了一段时间，</span>zed<span style="">觉得栅栏非常不美观。因此，他想给栅栏涂上颜色。问题是，</span>zed<span style="">的刷子宽度只有</span>1<span style="">，也就是说，一次只能将连续的一排或一列格子涂上颜色（长度任意）。</span>zed<span style="">想用最少的次数把栅栏全部涂上颜色（注意，一个格子不能重复涂色）。但是</span>zed<span style="">现在要去刷</span>DP<span style="">神题，没时间，所以这个问题就交给你了。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行为一个整数</span>N<span style="">，代表栅栏的宽度。</span></p><p><span style="">第二行为</span>N<span style="">个整数</span>h<sub>1</sub> ~ h<sub>n</sub><span style="">，代表从左向右每个竖条栅栏的高度。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体">输出文件有且仅有一行，一个整数</span>ans<span style="font-family:宋体">，代表将整个栅栏涂色所用最少次数。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style=""><strong>样例一：<br></strong></span></p><p><strong style=""><span style="font-family: Consolas;"><br>5</span></strong></p><p><strong style=""><span style="font-family: Consolas;">2 1 2 2 1</span></strong></p><p><strong style=""><span style="font-family: Consolas;"><br></span></strong></p><p><span style=""><strong>样例二：</strong></span></p><p><span style=""><strong><span style="font-family: Consolas;">2 2</span></strong><strong><span style="font-family: Consolas;"></span></strong><strong><span style="font-family: Consolas;"></span></strong></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""><strong>样例一：<br></strong></span></p><p><span style="font-family: 'comic sans ms';">3</span><br><br></p><p><span style=""></span></p><p style=""><span style=""><strong>样例一解释：</strong></span></p><p style=""> </p><p style=""> <img src="/source/codevs/codevs-4663/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00NjYzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE2MDEyMzExMDIxNF83NjUucG5n.png" title=""></p><p><span style=""><strong><br></strong></span><br></p><p><span style=""><strong>样例二：</strong></span></p><p><span style=""><strong><span style="font-family: Consolas;">2</span></strong><strong><span style="font-family: Consolas;"></span></strong></span></p><p><span style=""><strong><span style="font-family: Consolas;"><br></span></strong></span></p><p><span style=""><strong>样例解释二：</strong></span></p><p><img src="/source/codevs/codevs-4663/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00NjYzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE2MDEyMzExMDI1Nl84MTEucG5n.png" title=""></p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table cellpadding="0" cellspacing="0"><tbody><tr><td style="" width="277"><p style=""><span style=""><strong><span style="">数据组数</span></strong></span></p></td><td style="" width="277"><p style=""><strong><span style="">数据范围</span></strong></p></td></tr><tr><td style="" width="277"><p style=""><strong><span style="font-family: Consolas;">1 ~ 3</span></strong></p></td><td style="" width="277"><p style=""><strong><span style="font-family: Consolas;">N≤10</span><span style="">，</span><span style="font-family: Consolas;">1≤h<sub>i</sub>≤10<sup>9</sup></span></strong></p></td></tr><tr><td style="" width="277"><p style=""><strong><span style="font-family: Consolas;">4 ~ 10</span></strong></p></td><td style="" width="277"><p style=""><strong><span style="font-family: Consolas;">N≤5000</span><span style="">，</span><span style="font-family: Consolas;">1≤h<sub>i</sub>≤10<sup>9</sup></span></strong></p></td></tr></tbody></table><p></p>
</div>
</div>