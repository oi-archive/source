
# Description

<div class="content"><div>JSOI王国的交通网络可以看成是一个N个点M条边的带权有向图。图中每个顶点代表一个城市，每条边代表连接两个</div>
<div>城市的道路，同一对城市之间可能有多条道路连接。每条道路i有两个权值Di,和Ci，分别表示它的初始税收和在这</div>
<div>条道路上增加1单位的税收所需要承受的民众不满意程度。一条路径的税收是路径上所有道路的税收之和。</div>
<div>国王JS想要尽可能地增加从城市s到t旅行的税收，但这并不是个简单的事情。JSOI的民众非常聪明，无论你如何调</div>
<div>整税收，他们只会走从s到t的税收总和最小的路径，而另一方面，如果调整税收导致的不满意程度之和超过某个值</div>
<div>p将会引发社会危机。因此，JYY需要在承受的不满意程度之和不超过p的情况下使s到t的税收总和最小的路径的税</div>
<div>收尽可能地大。需要注意的是，JYY不能减少某条道路的税收，但他可以对任意道路增加任意实数单位的税收。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含五个整数，分别为N,M,P,S,T</div>
<div>
<div>接下来M行，每行四个整数Ui,Vi,Di,Ci描述一条从Ui,到Vi,的有向边</div>
<div>初始税收是Di,，每增加一单位的税收带来的不满意程度是Ci。</div>
<div>1≤N≤200,1≤M≤2×10O00,1≤P≤1000000</div>
<div>1≤Ci,Di≤10。保证至少存在一条从s到t的合法路径。</div>
</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个实数，表示可能的s到t的最大税收。</div>
<div>与标准答案误差在10^-4以内即认为正确。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 3 1 3<br/>
1 2 2 1<br/>
2 3 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">6.000000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

