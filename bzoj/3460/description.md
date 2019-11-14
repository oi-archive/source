
# Description

<div class="content"><p><span style="font-size: medium">WC2014后无数人来膜拜jc，但是来膜拜的人实在太多了， 而且很多人是一连膜拜好几天。所以jc给这些人建了一座树 形的宿舍，而根节点（1号节点）住着jc。然而，由于设计 的原因，宿舍中只有一个水龙头。于是晚上打水就成了问题。 所有人都有一个大小不同的水桶，第i个结点住着的人的水 桶灌满要Ti的时间。水龙头一开始在jc的宿舍，但是水龙 头的位置会发生变化。当一个人去打水，他走的一定是到水 龙头的最短距离，而且他路过的所有宿舍中住的人都会和他 一起去打水。现在有n个人入住，发生了m个事件。 </span></p>
<p><span style="font-size: medium">1.C i 表示水龙头在第i个宿舍 </span></p>
<p><span style="font-size: medium">2.Q i 表示住在i宿舍的人出发去打水。 </span></p>
<p><span style="font-size: medium">对于每个Q i，你需要告诉jc这次去打水的所有人最少的 总等待时间。 </span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行三个整数n,m,key，接下来一行n个整数 表示Ti（小于等于10^7），接下来一行n个数表示每个节点 的父亲，保证根节点的父亲为0。接下来m行每行表述一个 事件。对于每个Q操作，若输入为Q k，则实际的k=(k+(pre mod 2)*key) mod n+1，pre为上一个询问的答案，若是第一个 询问则pre=0。一开始水龙头在1号节点。 </span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每个Q事件输出一行，为答案。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata"> <br/>
3 2 0<br/>
2 2 1<br/>
0 3 1<br/>
C 3<br/>
Q 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
</span></div>

# Hint

<div class="content"><p></p><p> N&lt;=50000,M&lt;=50000,Key&lt;=10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By jiry_2 XXY杯省选模拟题">By jiry_2 XXY杯省选模拟题</a></p></div>

