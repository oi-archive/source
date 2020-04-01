
# Description

<div class="content"><div>在JIH考察的地图中有N个城市，被公路依次连成了一个环，JIH想在这些城市中建一个玩具厂。城市和公路都被编号为1..N，i号公路连接i-1号城市与i号城市（1号公路连接N号城市与1号城市），每个城市对玩具的需求为wi，每条公路的长度为di。当JIH在第i号城市建玩具厂时，JIH需要将玩具运输到其他城市（当然i城市除外）。设第i号城市到第j号城市的两条路径长度分别为l1、l2，则将玩具运输到第j号城市的费用为l1*l2*wj。总的运输费用为将玩具运到所有城市的运输费用的总和。</div>
<div>JIH当然想要总的运输费用最少，所以他会选最优的城市建玩具厂，如果有多个最优的城市，小月会等概率的选取其中一个建玩具厂。</div>
<div>由于JIH的调查工作没做好，只知道1..N-1号城市的wi，而N号城市的wi只知道它的取值范围[a,b]，假设wi的值在实数区间[a,b]上的概率是均匀分布的。现在JIH只好去进行第二次调查，于是我们想知道每个城市建玩具厂的概率是多少。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行有三个正整数N，a，b。</div>
<div>接下来N-1行每行一个正实数，为w[1]到w[N-1]。</div>
<div>接下来N行每行一个正实数，为d[1]到d[N]。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>N行，每行一个实数，表示在第i个城市建厂的概率</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1 100<br/>
50<br/>
25<br/>
25<br/>
50<br/>
1<br/>
2<br/>
3<br/>
2<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.090<br/>
0.000<br/>
0.000<br/>
0.090<br/>
0.821</span></div>

# Hint

<div class="content"><p></p><div>当w[5]&lt;18.75时，将在1或4号城市建玩具厂，当w[5]&gt;18.75时，将在5号城市建玩具厂，</div><br/>
<div>当w[5]=18.75时，将在1或4或5建玩具厂。</div><br/>
<div>100%的数据中：N&lt;=100000,a&lt;=b&lt;=10000,w[i]&lt;=10000,d[i]&lt;=10。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

