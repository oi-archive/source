
# Description

<div class="content"><div>　　M公司是一个非常庞大的跨国公司，在许多国家都设有它的下属分支机构或部门。为了让分布在世界各地的N个</div>
<div>部门之间协同工作，公司搭建了一个连接整个公司的通信网络。该网络的结构由N个路由器和N-1条高速光缆组成。</div>
<div>每个部门都有一个专属的路由器，部门局域网内的所有机器都联向这个路由器，然后再通过这个通信子网与其他部</div>
<div>门进行通信联络。该网络结构保证网络中的任意两个路由器之间都存在一条直接或间接路径以进行通信。 高速光</div>
<div>缆的数据传输速度非常快，以至于利用光缆传输的延迟时间可以忽略。但是由于路由器老化，在这些路由器上进行</div>
<div>数据交换会带来很大的延迟。而两个路由器之间的通信延迟时间则与这两个路由器通信路径上所有路由器中最大的</div>
<div>交换延迟时间有关。作为M公司网络部门的一名实习员工，现在要求你编写一个简单的程序来监视公司的网络状况</div>
<div>。该程序能够随时更新网络状况的变化信息（路由器数据交换延迟时间的变化），并且根据询问给出两个路由器通</div>
<div>信路径上延迟第k大的路由器的延迟时间。【任务】 你的程序从输入文件中读入N个路由器和N-1条光缆的连接信息</div>
<div>，每个路由器初始的数据交换延迟时间Ti，以及Q条询问（或状态改变）的信息。并依次处理这Q条询问信息，它们</div>
<div>可能是： 1. 由于更新了设备，或者设备出现新的故障，使得某个路由器的数据交换延迟时间发生了变化。 2. 查</div>
<div>询某两个路由器a和b之间的路径上延迟第k大的路由器的延迟时间。</div></div>

# Input

<div class="content"><div>
<div>
<div>第一行为两个整数N和Q，分别表示路由器总数和询问的总数。</div>
<div>第二行有N个整数，第i个数表示编号为i的路由器初始的数据延迟时间Ti。</div>
<div>紧接着N-1行，每行包含两个整数x和y。表示有一条光缆连接路由器x和路由器y。</div>
<div>紧接着是Q行，每行三个整数k、a、b。</div>
<div>如果k=0，则表示路由器a的状态发生了变化，它的数据交换延迟时间由Ta变为b</div>
<div>如果k&gt;0，则表示询问a到b的路径上所经过的所有路由器（包括a和b）中延迟</div>
<div>第k大的路由器的延迟时间。</div>
<div>注意N,Q&lt;=80000,任意一个路由器在任何时刻都满足延迟时间小于10^8。</div>
<div>对于所有询问满足0&lt;=K&lt;=N</div>
</div>
</div></div>

# Output

<div class="content"><div>
<div>对于每一个第二种询问（k&gt;0），输出一行。包含一个整数为相应的延迟时间。</div>
<div>如果路径上的路由器不足k个，则输出信息“invalidrequest!”</div>
<div>（全部小写不包含引号，两个单词之间有一个空格）。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
5 1 2 3 4<br/>
3 1<br/>
2 1<br/>
4 3<br/>
5 3<br/>
2 4 5<br/>
0 1 2<br/>
2 2 3<br/>
2 1 4<br/>
3 3 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2<br/>
2<br/>
invalid request!</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

