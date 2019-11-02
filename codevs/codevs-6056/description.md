<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>培训时，老师出了一道将1000000以内的整数N拆分为多个单调不降的2的整次方之和，问有多少种方式能够达到N；</p><p>皮皮虾的主人觉得这题太萎了，根本显示不出他的算法的优越性，于是，他为了卡掉O（n）时间复杂度O（n）空间复杂度的标程，他和他的皮皮虾打了一个赌：</p><p>99%的人都没有A这道题，否则他就带皮皮虾去火星旅行，皮皮虾很想去火星旅行，请你帮帮皮皮虾赢这个赌注；</p><p>请输出N的组合方案数 mod 1000000000 的值;<br></p><p><img src="/source/codevs/codevs-6056/img/aHR0cDovL2kuc3NpbWcuY24vaW1hZ2VzLzIwMTcvMDIvMjcvMzAxOGFhNDg4N2RmNGNmMjllZTliYTA0ODdjNDMwNGYuanBn.jpg"></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个long long范围内的整数N；<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数 组合方案数mod 1000000000 的值；<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围：N&lt;=2^63-1;</p><p><br></p><p>样例数据解释：</p><p style="">7 = 1+1+1+1+1+1+1</p><p style="">7 = 1+1+1+1+1 +2</p><p style="">7 = 1+1+1+2+2</p><p style="">7 = 1+2+2+2</p><p style="">7 = 1+1+1+4</p><p style="">7 = 1+2+4</p><p style="">所以对于7，共6种拆分方式。</p><p><br></p>
</div>
</div>