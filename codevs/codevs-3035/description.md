<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>小E同学非常喜欢书法，他听说NOI2013已经开始了，想题一幅“NOI”的字送给大家。</span></p>
<p><span>小E有一张非常神奇的纸, 纸可以用一个n行m列的二维方格矩阵来表示，为了描述方便，我们定义矩阵左下角方格坐标为(1,1)，右上角方格坐标为(m,n);矩阵的每个方格有一个整数的幸运值。在格子上面写字可以增加大家的幸运度，幸运度的大小恰好是所有被笔写到的方格的幸运值之和。现在你要在上面写上’N’, ’O’, ’I’三个字母。</span></p>
<p>下面给出3个书法字的定义：</p>
<p>1、’N’由若干 (≥3) 个边平行于坐标轴的矩形组成.设由K个矩形组成，标号1~K,第i个矩形的左下角方格坐标设为(L<sub>i</sub>,B<sub>i</sub>),右上角设为(R<sub>i</sub>,T<sub>i</sub>),要求满足：</p>
<p><span>a)L<sub>i</sub>≤R<sub>i</sub>,B<sub>i</sub>≤T<sub>i</sub>;</span></p>
<p><span>b)对任意 1&lt;i≤K，有 L<sub>i</sub>=R<sub>i−1</sub>+1；</span></p>
<p><span>c)对任意 3≤i&lt;K，有 B<sub>i−1</sub>−1≤T<sub>i</sub>≤T<sub>i−1</sub>，B<sub>i</sub>≤B<sub>i−1</sub>；</span></p>
<p><span>d)B<sub>2</sub>&gt;B<sub>1</sub>，T<sub>2</sub>=T<sub>1</sub>，B<sub>K−1</sub>=B<sub>K</sub>， T<sub>K−1</sub>&lt;T<sub>K</sub>；</span></p>
<p>2、’O’由一个大矩形A，挖去一个小矩形B得到，这两个矩形的边都平行于<span>坐标轴。设大矩形A左下角的方格坐标为(u,v),长为W，宽为H，则</span><span>小矩形B满足左下角方格坐标为(u+1,v+1),长W-2，宽H-2；要求满足：</span></p>
<p>a) W≥3,H≥3；</p>
<p>b) u&gt;R<sub>K</sub>+1；</p>
<p>3、<span>’I’为3个边平行于坐标轴的从下到上的实心矩形组成，从下到上依次标</span><span>号为1,2,3，第i个矩形的左下角格子坐标设为(P<sub>i</sub>,Q<sub>i</sub>),右上角格子坐标设为(G<sub>i</sub>,H<sub>i</sub>);要求满足：</span></p>
<p><span>a) P<sub>i</sub>≤G<sub>i</sub>,Q<sub>i</sub>≤H<sub>i</sub>；</span></p>
<p>b) P<sub>1</sub>=P<sub>3</sub>&gt;u+W,G<sub>1</sub>=G<sub>3</sub>；</p>
<p>c) Q<sub>1</sub>=H<sub>1</sub>=Q<sub>2</sub>−1,H<sub>2</sub>+1=Q<sub>3</sub>=H<sub>3</sub>；</p>
<p>d) P<sub>1</sub>&lt;P<sub>2</sub>≤G<sub>2</sub>&lt;G<sub>1.</sub></p>
<p>下图是一个’N’, ’O’, ’I’的例子。</p>
<p>另外，所有画的图形均不允许超过纸张的边界。现在小E想要知道，他能画出的最大幸运度是多少。</p>

<img src="/source/codevs/codevs-3035/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zMDM1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8zMDM1LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>【输入格式】<br>输入文件penman.in的第一行包含两个正整数n和m，分别表示矩阵的行数和列数。<br>接下来n行，每行有m个整数，第i+1 行的第j个数表示格子(j,n−i+1)的幸运值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>【输出格式】<br />输出到文件penman.out中，输出一个整数T，表示小E能够获得的最大幸运度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br><span>3 13</span><br><span>1 1 -1 -1 1 -1 1 1 1 -1 1 1 1</span><br><span>1 -1 1 -1 1 -1 1 -1 1 -1 -1 1 -1</span><br><span>1 -1 -1 1 1 -1 1 1 1 -1 1 1 1</span></p>
<p>【样例输入2】<br>3 13<br>-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1<br>-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1<br>-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br>24</p>
<p>【样例输出2】</p>
<p>-20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 所有的测试数据， 保证 n≥3,m≥12。</p>
<p>已经更换为官方测试数据。</p>
</div>
</div>