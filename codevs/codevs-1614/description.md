<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一家电信公司正在北京城搭建一个GSM 网络。城市里共有n 个房子需要被<br>信号覆盖。由于经费的限制，电信公司只能安装一个天线。<br>这里将每个房子用一个点坐标来表示。为了简化天线的放置，电信公司将会<br>选择其中的3 个房子作一个外接圆，然后将天线放在圆的中心，所有位于这个圆<br>内或者圆的边界上的房子都将被天线的信号所覆盖。<br>电信公司将会随机选择城市中的3 个房子来搭建天线，他们想知道在所有可<br>能放置天线的方案中平均会有多少个房子被信号覆盖。<br>例如，假设共有4 个房子A, B, C, D，它们的位置如下图：<br>如果我们选择ABC 或者BCD 三个点搭建的外接圆，所有的房子都会被覆盖。<br>如果我们选择ACD 或者ABD，剩下的房子将不会在天线的信号覆盖范围内。因<br>此平均有(4 + 4 + 3 + 3) / 4 = 3.50 个房子被信号覆盖。<br>给定所有房子的位置，你的任务是计算平均有多少个房子被信号覆盖。假定<br>每一个房子都有一个二维的整数坐标，并且保证任何三个房子都不在同一条直线<br>上，任何四个房子都不在同一个圆上。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行包含一个正整数n, 表示房子的总数。接下来有n 行，分别表示<br>每一个房子的位置。对于i = 1, 2, .., n, 第i 个房子的坐标用一对整数xi 和yi 来表<br>示，中间用空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件包含一个实数，表示平均有多少个房子被信号所覆盖，需保证输出<br />结果与精确值的绝对误差不超过0.000001。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>0 2<br>4 4<br>0 0<br>2 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3.500000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据保证，对于i = 1, 2, .., n, 第i 个房子的坐标(xi, yi)为整数且<br>–1,000,000 ≤ xi, yi ≤ 1,000,000. 任何三个房子不在同一条直线上，任何四个房子不<br>在同一个圆上；<br>40%的数据，n ≤ 100；<br>70%的数据，n ≤ 500；<br>100%的数据，3 ≤ n ≤ 1,500。</p>
</div>
</div>