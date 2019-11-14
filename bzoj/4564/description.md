
# Description

<div class="content"><div>
<div>一天rin来到了一个遥远的都市。这个都市有n个建筑，编号从1到n，其中市中心编号为1，这个都市有m条双向通</div>
<div>行的街道，每条街道连接着两个建筑，其中某些街道首尾相连连接成了一个环。rin通过长时间的走访，已经清楚</div>
<div>了这个都市的两个特点：1. 从市中心出发可以到达所有的建筑物。2. 任意一条街道最多存在与一个简单环中。令</div>
<div>rin心花怒放的是，每个建筑物都会有拉面售卖。拉面有很多不同的种类，但对于rin而言只有油腻程度的不同，因</div>
<div>此我们把油腻程度相同的拉面看做同一种拉面。由于不同建筑物的拉面的油腻程度可能不同，我们用一个正整数来</div>
<div>表示拉面的油腻程度。要知道，拉面可是rin的最爱，但是现在到了下班高峰期，都市的交通变得非常的堵塞。 ri</div>
<div>n只能通过没有被堵死的街道通行，去品尝所在建筑物的拉面。现在rin想知道，如果她正在编号为x的建筑物，那</div>
<div>么在从市中心到x的所有简单路径经过的街道都被堵死的情况下，rin可以品尝到的拉面中（注意没有出现的拉面是</div>
<div>不能算在里面的）：</div>
<div>1. 油腻程度≤ y且品尝次数为奇数次的拉面有多少种？</div>
<div>2. 油腻程度≤ y且品尝次数为偶数次的拉面有多少种？</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行两个正整数n,m，含义如题所示第二行一共N个正整数，第i个数Ai表示第i个建筑物出售的拉面的油腻程度。</div>
<div>接下来M行，每行两个正整数x,y，表示在建筑物x,y之间有一条双向通行的街道。数据保证1&lt;=x&lt;y&lt;=N接下来一行一</div>
<div>个正整数Q，表示询问个数。接下来Q行每行三个非负整数ty,x,y,x表示询问的建筑物编号，y表示油腻程度的限制</div>
<div>，ty=0时表示询问偶数，ty=1表示询问奇数。N&lt;=100000,M&lt;=150000,Q&lt;=100000,Ai&lt;=10^6提示：请注意数据范围中</div>
<div>的&lt;=，特殊条件中提到的??均为询问中的y，对于所有的数据，有y&lt;=10^6</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><p>一共Q行，对于每个询问输出一个答案。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 12<br/>
1 10 4 5 2 10 1 8 4 8 <br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 5<br/>
4 6<br/>
4 7<br/>
7 8<br/>
2 9<br/>
8 10<br/>
1 6<br/>
8 10<br/>
4 7<br/>
10<br/>
0 3 9<br/>
1 7 6<br/>
0 5 2<br/>
1 10 9<br/>
0 5 7<br/>
1 7 4<br/>
0 7 3<br/>
1 2 7<br/>
0 3 4<br/>
0 3 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
0<br/>
1<br/>
0<br/>
1<br/>
0<br/>
2<br/>
0<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

