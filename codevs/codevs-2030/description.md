<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>N个不同的颜色的不透明的长方形(1 &lt;= N &lt;= 1000)被放置在一张横宽为A竖长为B的白纸上。 这些长方形被放置时，保证了它们的边与白纸的边缘平行。 所有的长方形都放置在白纸内，所以我们会看到不同形状的各种颜色。 坐标系统的原点(0,0)设在这张白纸的左下角，而坐标轴则平行于边缘。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>按顺序输入放置长方形的方法。第一行输入的是那个放在底的长方形(即白纸)。</p>
<p>第 1 行: A ， B 和 N由空格分开 (1 &lt;=A, B&lt;=10,000)</p>
<p>第 2 到N+1行: 为五个整数　llx, lly, urx, ury, color　这是一个长方形的左下角坐标，右上角坐标(x+1,y+1)和颜色。</p>
<p>颜色 1和底部白纸的颜色相同。 (1 &lt;= color &lt;= 2500)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出且仅输出所有能被看到颜色，和该颜色的总面积(可以由若干个不连通的色块组成)，按color增序排列。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>20 20 3
2 2 18 18 2
0 8 19 19 3
8 0 10 19 4</pre>
<pre> </pre>
<p>请注意：被(0,0)和(2,2)所描绘的是2个单位宽、2个单位高的区域</p>
<p>这里有一个示意图输入：</p>
<pre>11111111111111111111
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
33333333443333333331
11222222442222222211
11222222442222222211
11222222442222222211
11222222442222222211
11222222442222222211</pre>
<pre>11222222442222222211
11111111441111111111
11111111441111111111</pre>
<pre><span>'4'在(8,0)与(10,19)形成的是宽为2的区域,而不是3.（也就是说，4形成的区域包含(8,0)和(8,1) ，而不是(8,0)和(8,2)） 。</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>1 91
2 84
3 187
4 38</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>一个记录所有点的数组太大了；内存最大16MB。</p>
<p>掌握长方形的坐标动向，当发生覆盖时把长方形分开。</p>
</div>
</div>