
# Description

<div class="content"><p> 一条东西走向的穆西河将巴邻旁市一分为二，分割成了区域 A 和区域 B。</p>
<div>每一块区域沿着河岸都建了恰好 1000000001 栋的建筑，每条岸边的建筑都从 0 编号到 1000000000。相邻的每对建筑相隔 1 个单位距离，河的宽度也是 1 个单位长度。区域 A 中的 i 号建筑物恰好与区域 B 中的 i 号建筑物隔河相对。</div>
<div>城市中有 N 个居民。第 i 个居民的房子在区域 Pi 的 Si 号建筑上，同时他的办公室坐落在 Qi 区域的 Ti 号建筑上。一个居民的房子和办公室可能分布在河的两岸，这样他就必须要搭乘船只才能从家中去往办公室，这种情况让很多人都觉得不方便。为了使居民们可以开车去工作，政府决定建造不超过 K 座横跨河流的大桥。</div>
<div>由于技术上的原因，每一座桥必须刚好连接河的两岸，桥梁必须严格垂直于河流，并且桥与桥之间不能相交。当政府建造最多 K 座桥之后，设 Di 表示第 i 个居民此时开车从家里到办公室的最短距离。请帮助政府建造桥梁，使得 D1+D2+⋯+DN 最小。</div>
<div></div></div>

# Input

<div class="content"><p>输入的第一行包含两个正整数 K 和 N，分别表示桥的上限数量和居民的数量。</p>
<div>接下来 N 行，每一行包含四个参数：Pi,Si,Qi 和 Ti，表示第 i 个居民的房子在区域 Pi 的 Si 号建筑上，且他的办公室位于 Qi 区域的 Ti 号建筑上。</div>
<div></div></div>

# Output

<div class="content"><p>输出仅为一行，包含一个整数，表示 D1+D2+⋯+DN 的最小值。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 5<br/>
B 0 A 4<br/>
B 1 B 3<br/>
A 5 B 7<br/>
B 2 A 6<br/>
B 1 A 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">24</span></div>

# Hint

<div class="content"><p></p><p> 子任务</p><br/>
<div>所有数据都保证：Pi 和 Qi 为字符 “A” 和 “B” 中的一个， 0≤Si,Ti≤1000000000，同一栋建筑内可能有超过 1 间房子或办公室（或二者的组合，即房子或办公室的数量同时大于等于 1）。</div><br/>
<div></div><br/>
<div>子任务 1 （8 分）</div><br/>
<div>K=1</div><br/>
<div>1≤N≤1000</div><br/>
<div>子任务 2 （14 分）</div><br/>
<div>K=1</div><br/>
<div>1≤N≤100000</div><br/>
<div>子任务 3 （9 分）</div><br/>
<div>K=2</div><br/>
<div>1≤N≤100</div><br/>
<div>子任务 4 （32 分）</div><br/>
<div>K=2</div><br/>
<div>1≤N≤1000</div><br/>
<div>子任务 5 （37 分）</div><br/>
<div>K=2</div><br/>
<div>1≤N≤100000</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

