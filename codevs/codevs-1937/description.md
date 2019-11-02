<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>栋栋有一块长方形的地，他在地上种了一种能量植物，这种植物可以采集太阳光的能量。在这些植物采集能量后，栋栋再使用一个能量汇集机器把这些植物采集到的能量汇集到一起。</p>
<p>栋栋的植物种得非常整齐，一共有n列，每列有m棵，植物的横竖间距都一样，因此对于每一棵植物，栋栋可以用一个坐标(x, y)来表示，其中x的范围是1至n，表示是在第x列，y的范围是1至m，表示是在第x列的第y棵。</p>
<p>由于能量汇集机器较大，不便移动，栋栋将它放在了一个角上，坐标正好是(0, 0)。</p>
<p>能量汇集机器在汇集的过程中有一定的能量损失。如果一棵植物与能量汇集机器连接而成的线段上有k棵植物，则能 量的损失为2k + 1。例如，当能量汇集机器收集坐标为(2, 4)的植物时，由于连接线段上存在一棵植物(1, 2)，会产生3的能量损失。注意，如果一棵植物与能量汇集机器连接的线段上没有植物，则能量损失为1。现在要计算总的能量损失。</p>
<p>下面给出了一个能量采集的例子，其中n = 5，m = 4，一共有20棵植物，在每棵植物上标明了能量汇集机器收集它的能量时产生的能量损失。</p>
<p> </p>
<p>在这个例子中，总共产生了36的能量损失。</p>

<img src="/source/codevs/codevs-1937/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xOTM3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NjM2NzY5MC4wNTAuNTExOTM0OTYwMDEzLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件energy.in仅包含一行，为两个整数n和m。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件energy.out仅包含一个整数，表示总共产生的能量损失。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<h2>【样例输入1】</h2>
<p>5 4</p>
<h2>【样例输入2】</h2>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<h2><span style="">【样例输出1】</span></h2>
<p>36</p>
<h2>【样例输出2】</h2>
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据：1 ≤ n, m ≤ 10；</p>
<p>对于50%的数据：1 ≤ n, m ≤ 100；</p>
<p>对于80%的数据：1 ≤ n, m ≤ 1000；</p>
<p>对于90%的数据：1 ≤ n, m ≤ 10,000；</p>
<p>对于100%的数据：1 ≤ n, m ≤ 100,000。</p>
</div>
</div>