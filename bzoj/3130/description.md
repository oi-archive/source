
# Description

<div class="content"><p><span style="font-size: medium"> Alice和Bob在图论课程上学习了最大流和最小费用最大流的相关知识。<br/>
    最大流问题：给定一张有向图表示运输网络，一个源点S和一个汇点T，每条边都有最大流量。一个合法的网络流方案必须满足：(1)每条边的实际流量都不超过其最大流量且非负；(2)除了源点S和汇点T之外，对于其余所有点，都满足该点总流入流量等于该点总流出流量；而S点的净流出流量等于T点的净流入流量，这个值也即该网络流方案的总运输量。最大流问题就是对于给定的运输网络，求总运输量最大的网络流方案。</span></p>
<p><span style="font-size: medium"><br/>
  上图表示了一个最大流问题。对于每条边，右边的数代表该边的最大流量，左边的数代表在最优解中，该边的实际流量。需要注意到，一个最大流问题的解可能不是唯一的。    对于一张给定的运输网络，Alice先确定一个最大流，如果有多种解，Alice可以任选一种；之后Bob在每条边上分配单位花费（单位花费必须是非负实数），要求所有边的单位花费之和等于P。总费用等于每一条边的实际流量乘以该边的单位花费。需要注意到，Bob在分配单位花费之前，已经知道Alice所给出的最大流方案。现茌Alice希望总费用尽量小，而Bob希望总费用尽量大。我们想知道，如果两个人都执行最优策略，最大流的值和总费用分别为多少。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">    第一行三个整数N，M，P。N表示给定运输网络中节点的数量，M表示有向边的数量，P的含义见问题描述部分。为了简化问题，我们假设源点S是点1，汇点T是点N。<br/>
    接下来M行，每行三个整数A，B，C，表示有一条从点A到点B的有向边，其最大流量是C。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">第一行一个整数，表示最大流的值。<br/>
第二行一个实数，表示总费用。建议选手输出四位以上小数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 1<br/>
1 2 10<br/>
2 3 15</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
10.0000<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【样例说明】<br/><br/>
    对于Alice，最大流的方案是固定的。两条边的实际流量都为10。<br/><br/>
    对于Bob，给第一条边分配0.5的费用，第二条边分配0.5的费用。总费用<br/><br/>
为：10*0.5+10*0.5=10。可以证明不存在总费用更大的分配方案。<br/><br/>
【数据规模和约定】<br/><br/>
    对于20%的测试数据：所有有向边的最大流量都是1。<br/><br/>
    对于100%的测试数据：N &lt; = 100，M &lt; = 1000。<br/><br/>
    对于l00%的测试数据：所有点的编号在I..N范围内。1 &lt; = 每条边的最大流<br/><br/>
量 &lt; = 50000。1 &lt; = P &lt; = 10。给定运输网络中不会有起点和终点相同的边。<br/><br/>
  </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

