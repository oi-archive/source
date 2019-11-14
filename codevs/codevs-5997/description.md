<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    ZC神犇最近迷上了出题,他坑了机房一位又一位的人,于是有一天,报复终于来了,他在打完近10000000000000000 mod 10行代码的时候,由于代码量过大(?),编译器带着ZC神犇一起进入了编译的世界,ZC到了这个世界,不屑的看着眼前的010101010101010101...当然，作为神犇的他不畏惧如此,他一直看着自己的近10000000000000000 mod 10行代码而懒得找出路(?)</p><p>    其实出口是确定的(ZC神犇AC的那个位置),但在这个地方,走过一些路口都要收取一定的费用,ZC神犇第一次来到这个地方,想把<strong>所有</strong>的路都走一遍（他很有钱),但是他也很吝啬,于是想让您找一条最省钱的路径（ZC身手不好，只能往<strong>四个方向</strong>走）</p><p>    给定一个01矩阵,起点为1,1，终点为n,n,当跨越到<strong>异类</strong>时，就要收取费用(如从0到1收取1,从1到0收取也是1,从0到0 or 从1到1都不需要收取费用）</p><p>    ZC从起点出发，求最少他要花多少钱才能走完全部的路去出题（坑人？）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个整数n，表示01矩阵的边长<br></p><p>第2-n+1行，每行n个0或1的数，表示01矩阵</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数ans，表示ZC最少要花的钱数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>000</p><p>111</p><p>000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">1&lt;=n&lt;=500；</p><p style="">矩阵里的数保证只有0和1.</p><p style="">ans保证&lt;maxlongint(INT_MAX)<br></p><p style=""><br></p><p>ZC从1,1出发,到3,3结束</p><p>(1,1)-(1,2)-(1,3)-(2,3)-(2,2)-(2,1)-(3,1)-(3,2)-(3,3)为花最少钱的路径</p><p>只有在(1,3)-(2,3)需要付1元</p><p>(2,1)-(3,1)需要付1元</p><p>所以输出2</p><p><br></p><p>By hjwjr</p><p><br></p>
</div>
</div>