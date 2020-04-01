<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    Alice 和Bob 在图论课程上学习了最大流和最小费用最大流的相关知识。 最大流问题：给定一张有向图表示运输网络，一个源点S 和一个汇点T，每 条边都有最大流量。一个合法的网络流方案必须满足：(1)每条边的实际流量都不超过其最大流量且非负；(2)除了源点S 和汇点T 之外，对于其余所有点，都 满足该点总流入流量等于该点总流出流量；而S 点的净流出流量等于T 点的净 流入流量，这个值也即该网络流方案的总运输量。最大流问题就是对于给定的运 输网络，求总运输量最大的网络流方案。</p>
<p>    上图表示了一个最大流问题。对于每条边，右边的数代表该边的最大流量， 左边的数代表在最优解中，该边的实际流量。需要注意到，一个最大流问题的解 可能不是唯一的。 <br> 对于一张给定的运输网络，Alice 先确定一个最大流，如果有多种解，Alice 可以任选一种；之后Bob 在每条边上分配单位花费(单位花费必须是非负实数)， 要求所有边的单位花费之和等于P。总费用等于每一条边的实际流量乘以该边的单位花费。需要注意到，Bob 在分配单位花费之前，已经知道Alice 所给出的最大流方案。 <br>    现在Alice 希望总费用尽量小，而Bob 希望总费用尽量大。我们想知道，如果两个人都执行最优策略，最大流的值和总费用分别为多少。</p>

<img src="/source/codevs/codevs-1967/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xOTY3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTk2Ny5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个整数N，M，P。N 表示给定运输网络中节点的数量，M 表示有 向边的数量，P 的含义见问题描述部分。为了简化问题，我们假设源点S 是点1，汇点T 是点N 。 <br> 接下来M 行，每行三个整数A，B，C，表示有一条从点A 到点B 的有向边，其最大流量是C。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行一个整数，表示最大流的值。 <br /> 第二行一个实数，表示总费用。输出5位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 1 <br> 1 2 10 <br> 2 3 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10 <br> 10.00000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>对于Alice，最大流的方案是固定的。两条边的实际流量都为10。 <br> 对于Bob，给第一条边分配0.5 的费用，第二条边分配0.5 的费用。总费用 为：10*0.5+10*0.5=10 。可以证明不存在总费用更大的分配方案。</p>
<p>【数据规模和约定】</p>
<p>对于20%的测试数据：所有有向边的最大流量都是1。 <br> 对于100%的测试数据：N≤100，M≤1000。 <br> 对于100%的测试数据：所有点的编号在1..N 范围内。1≤每条边的最大流 量≤50000。1≤P≤10。给定运输网络中不会有起点和终点相同的边。</p>
</div>
</div>