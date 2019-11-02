<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>小 T 是一名质量监督员，最近负责检验一批矿产的质量。这批矿产共有n 个矿石，从1到n 逐一编号，每个矿石都有自己的重量wi 以及价值vi。检验矿产的流程是：见图</div>
<div> </div>
<div>若这批矿产的检验结果与所给标准值S 相差太多，就需要再去检验另一批矿产。小T不想费时间去检验另一批矿产，所以他想通过调整参数W 的值，让检验结果尽可能的靠近标准值S，即使得S-Y 的绝对值最小。请你帮忙求出这个最小值。</div>

<img src="/source/codevs/codevs-1138/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMTM4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMTM4XzEucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含三个整数 n，m，S，分别表示矿石的个数、区间的个数和标准值。<br>接下来的 n 行，每行2 个整数，中间用空格隔开，第i+1 行表示i 号矿石的重量wi 和价值vi 。<br>接下来的 m 行，表示区间，每行2 个整数，中间用空格隔开，第i+n+1 行表示区间[Li,Ri]的两个端点Li 和Ri。注意：不同区间可能重合或相互重叠。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个整数，表示所求的最小值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3 15<br>1 5<br>2 5<br>3 5<br>4 5<br>5 5<br>1 5<br>2 4<br>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>当 W 选4 的时候，三个区间上检验值分别为20、5、0，这批矿产的检验结果为25，此时与标准值S 相差最小为10。</p>
<p><br>数据范围<br>对于 10%的数据，有1≤n，m≤10；<br>对于 30%的数据，有1≤n，m≤500；<br>对于 50%的数据，有1≤n，m≤5,000；<br>对于 70%的数据，有1≤n，m≤10,000；<br>对于 100%的数据，有1≤n，m≤200,000，0 &lt; wi, vi≤10<sup><sub>6</sub></sup>，0 &lt; S≤10<sup>12</sup>，1≤Li≤Ri≤n。</p>
</div>
</div>