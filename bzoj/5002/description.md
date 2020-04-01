
# Description

<div class="content"><div>在Dingilville市城市交通的安排很不寻常，公路连接着路口，在两个不同的路口之间最多有一条公路连接，没有公路会连接一个路口自身。正反向通过一条道路的时间是相同的，在每一个路口都有一个交通灯，在任意时刻它要么是蓝色的要么是紫色的，这些灯的颜色是定期交换的：蓝色持续一段时间，紫色持续一段时间。当一条公路两边的交通灯颜色相同时才允许汽车离开一个路口去另一个路口。如果一辆车到达一个路口时的瞬间交通灯的颜色改变了，那就需要重新考虑新的颜色。车辆允许在一个路口进行等待。你将得到关于城市的下列信息：</div>
<div>1:每条公路通过所需要的时间(整数)</div>
<div>2:每一个路口两种交通灯的颜色的持续时间(整数)</div>
<div>3:和每个路口的交通灯的初始颜色和持续时间(整数) </div>
<div>你的任务就是寻找一辆车从给定起始路口到给定终止路口所需要的最短时间。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括两个数字：起始路口和终止路口。</div>
<div>第二行包含两个数字：n和m。n代表路口的个数，公路由1～n的整数来标识。 m代表公路的个数。</div>
<div>接下来的n行包含n个路口的信息：第(i+2)行给出了第i个路口的信息：Ci, riC, tiB, tiP。</div>
<div>C就是第i个路口的交通灯的初始颜色，要么是B(蓝色)或者P(紫色)。riC表示交通灯i初始颜色剩下来的时间。</div>
<div>tiB, tiP分别表示交通灯i对于B色持续时间和P色持续时间。</div>
<div>最后接下来的m行包含m条公路的信息，每行都有： i, j, lij。</div>
<div>路口i到路口j由这条公路连接。</div>
<div>2 &lt;= N &lt;= 1000 ；1 &lt;= M &lt;= 50000，1&lt;= riC, tiB, tiP, lij&lt;=100。</div>
<p></p></div>

# Output

<div class="content"><div>如果存在这样一条路径输出从起始路口到给定终止路口所需要的最短时间。</div>
<div>如果这样的路径不存在：输出0。 </div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 4<br/>
4 5<br/>
B 2 16 99<br/>
P 6 32 13<br/>
P 2 87 4<br/>
P 38 96 49<br/>
1 2 4<br/>
1 3 40<br/>
2 3 75<br/>
2 4 76<br/>
3 4 77<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">127</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

