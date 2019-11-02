<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>致力于建设全国示范和谐小村庄的<span style="font-family: 'Times New Roman';">H</span><span style="">村村长</span><span style="font-family: 'Times New Roman';">dadzhi</span><span style="">，决定在村中建立一个瞭望塔，以此加强村中的治安。</span></p>
<p>我们将<span style="font-family: 'Times New Roman';">H</span><span style="">村抽象为一维的轮廓。</span></p>
<p>我们可以用一条山的上方轮廓折线<span style="font-family: 'Times New Roman';">(</span>x1, y1), (x2, y2), …. (xn, yn)<span style="">来描述</span><span style="font-family: 'Times New Roman';">H</span><span style="">村的形状，这里</span>x1 &lt; x2 &lt; …&lt; xn。瞭望塔可以建造在<span style="font-family: 'Times New Roman';">[</span>x1, xn]<span style="">间的</span>任意位置<span style="font-family: 'Times New Roman';">, </span><span style="">但必须满足</span>从瞭望塔的顶端可以看到<span style="font-family: 'Times New Roman';">H</span><span style="">村的任意位置</span>。可见在不同的位置建造瞭望塔，所需要建造的高度是不同的。为了节省开支，<span style="font-family: 'Times New Roman';">dadzhi</span><span style="">村长希望建造的塔高度尽可能小。</span></p>
<p>请你写一个程序，帮助<span style="font-family: 'Times New Roman';">dadzhi</span><span style="">村长计算塔的最小高度。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数n<span style="">，表示轮廓折线的节点数目。接下来第一行n个整数</span><span style="font-family: 'Times New Roman';">, </span><span style="">为</span><span style="">x1 ~ xn. </span><span style="">第三行</span><span style="">n个整数，为y1 ~ yn。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅包含一个实数，为塔的最小高度，精确到小数点后三位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>1 2 4 5 6 7</p>
<p>1 2 2 4 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">60%</span><span style="">的数据， </span>N ≤ 60<span style="">；</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据， </span>N ≤ 300<span style="">，输入坐标绝对值不超过</span><span style="font-family: 'Times New Roman';">10</span>6，<strong>注意考虑实数误差带来的问题。</strong></p>
<p> </p>
</div>
</div>