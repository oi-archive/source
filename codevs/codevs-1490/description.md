<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>M公司是一个非常庞大的跨国公司，在许多国家都设有它的下属分支机构或部门。为了让分布在世界各地的N个部门之间协同工作，公司搭建了一个连接整个公司的通信网络。该网络的结构由N个路由器和N-1条高速光缆组成。每个部门都有一个专属的路由器，部门局域网内的所有机器都联向这个路由器，然后再通过这个通信子网与其他部门进行通信联络。该网络结构保证网络中的任意两个路由器之间都存在一条直接或间接路径以进行通信。</p>
<p> 高速光缆的数据传输速度非常快，以至于利用光缆传输的延迟时间可以忽略。但是由于路由器老化，在这些路由器上进行数据交换会带来很大的延迟。而两个路由器之间的通信延迟时间则与这两个路由器通信路径上所有路由器中最大的交换延迟时间有关。作为M公司网络部门的一名实习员工，现在要求你编写一个简单的程序来监视公司的网络状况。该程序能够随时更新网络状况的变化信息（路由器数据交换延迟时间的变化），并且根据询问给出两个路由器通信路径上延迟第k大的路由器的延迟时间。</p>
<p>你的程序从输入文件中读入N个路由器和N-1条光缆的连接信息，每个路由器初始的数据交换延迟时间T<sub>i</sub>，以及Q条询问（或状态改变）的信息。并依次处理这Q条询问信息，它们可能是：</p>
<p>1.        由于更新了设备，或者设备出现新的故障，使得某个路由器的数据交换延迟时间发生了变化。</p>
<p>2.        查询某两个路由器a和b之间的<strong>路径上延迟第k大</strong>的路由器的延迟时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件network.in中的第一行为两个整数N和Q，分别表示路由器总数和询问的总数。</p>
<p>第二行有N个整数，第i个数表示编号为i的路由器初始的数据延迟时间T<sub>i</sub>。</p>
<p>紧接着N-1行，每行包含两个整数x和y。表示有一条光缆连接路由器x和路由器y。</p>
<p>紧接着是Q行，每行三个整数k、a、b。如果k=0，则表示路由器a的状态发生了变化，它的数据交换延迟时间由T<sub>a</sub>变为b。如果k&gt;0，则表示询问a到b的路径上所经过的所有路由器（<strong>包括a和b</strong>）中延迟第k大的路由器的延迟时间。<strong>注意a可以等于b，此时路径上只有一个路由器。</strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">输出文件为network.out。对于每一个第二种询问（k&gt;0），输出一行。包含一个整数为相应的延迟时间。如果路径上的路由器不足k个，则输出信息&ldquo;invalid request!&rdquo;（<strong>全部小写不包含引号，两个单词之间有一个空格</strong>）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>       5 5</p>
<p>       5 1 2 3 4</p>
<p>       3 1</p>
<p>       2 1</p>
<p>       4 3</p>
<p>       5 3</p>
<p>       2 4 5</p>
<p>       0 1 2</p>
<p>       2 2 3</p>
<p>       2 1 4</p>
<p>       3 3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>       3</p>
<p>       2</p>
<p>       2</p>
<p>       invalid request!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100% 测试数据满足 n&lt;=80000，q&lt;=30000 。任意一个路由器在任何时刻都满足延迟时间小于10<sup>8</sup>。对于所有询问满足 。</p>
<p>       40% 测试数据满足所有询问中1&lt;=k&lt;=5 ,且路由器的延迟时间不会发生变化。</p>
<p>10% 测试数据满足n,q&lt;=8000 。</p>
</div>
</div>