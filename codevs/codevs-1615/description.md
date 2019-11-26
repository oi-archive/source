<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你在一家IT 公司为大型写字楼或办公楼（offices）的计算机数据做备份。<br>然而数据备份的工作是枯燥乏味的，因此你想设计一个系统让不同的办公楼彼此<br>之间互相备份，而你则坐在家中尽享计算机游戏的乐趣。<br>已知办公楼都位于同一条街上。你决定给这些办公楼配对（两个一组）。每<br>一对办公楼可以通过在这两个建筑物之间铺设网络电缆使得它们可以互相备份。<br>然而，网络电缆的费用很高。当地电信公司仅能为你提供K 条网络电缆，<br>这意味着你仅能为K 对办公楼（或总计2K 个办公楼）安排备份。任一个办公楼<br>都属于唯一的配对组（换句话说，这2K 个办公楼一定是相异的）。<br>此外，电信公司需按网络电缆的长度（公里数）收费。因而，你需要选择这<br>K 对办公楼使得电缆的总长度尽可能短。换句话说，你需要选择这K 对办公楼，<br>使得每一对办公楼之间的距离之和（总距离）尽可能小。<br>下面给出一个示例，假定你有5 个客户，其办公楼都在一条街上，如下图所<br>示。这5 个办公楼分别位于距离大街起点1km, 3km, 4km, 6km 和12km 处。电信<br>上例中最好的配对方案是将第1 个和第2 个办公楼相连，第3 个和第4 个办<br>公楼相连。这样可按要求使用K=2 条电缆。第1 条电缆的长度是3km―1km =<br>2km，第2 条电缆的长度是6km―4km = 2 km。这种配对方案需要总长4km 的网<br>络电缆，满足距离之和最小的要求。</p>

<img src="/source/codevs/codevs-1615/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjE1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NDk2NjA4NS4zMTAuMzc5MDM4MDk3NzQ5LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含整数n 和k，其中n（2 ≤ n ≤100 000）表示办公楼的数目，<br>k（1≤ k≤ n/2）表示可利用的网络电缆的数目。<br>接下来的n 行每行仅包含一个整数（0≤ s ≤1000 000 000）, 表示每个办公楼<br>到大街起点处的距离。这些整数将按照从小到大的顺序依次出现。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出应由一个正整数组成，给出将2K 个相异的办公楼连成k 对所需的网络<br />电缆的最小总长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2<br>1 <br>3 <br>4 <br>6<br>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的输入数据满足n≤20。<br>60%的输入数据满足n≤10 000。</p>
</div>
</div>