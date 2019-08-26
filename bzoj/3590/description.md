
# Description

<div class="content"><p><span style="font-size: medium">  4.20四川芦山地震发生后，抗震救灾委员会接到一个紧急任务，四川省给<br/>
该委员会发了一份地图，这份地图给出了该省一些城市的情况：任两个城市是<br/>
用一条或多条公路连接起来的，也可以没有公路连接，但是每个城市都可以直<br/>
接或间接地到达另外的城市，注意这些公路是可以双向行驶的。由于最近余震、<br/>
暴雨造成泥石流倾泻，使得车辆在这些公路上行驶很不安全，于是四川省决定<br/>
尽快对部分公路进行抢修，以保障救援车辆行车安全。<br/>
    该省对所有的公路情况都进行了勘察，分析估计了抢修某段公路所需要花<br/>
费的时间，并记录在地图中。现在该省希望抗震救灾委员会能找到一个方案，<br/>
该方案决定出哪些公路需要抢修，使得抢修后的公路仍能保证任意两个城市之<br/>
间都能直接或间接地相连，同时为了安全起见，即使某一条抢修的公路被泥石<br/>
流阻断了，任意两城市仍能保持这个性质。由于时间紧迫，抗震救灾委员会还<br/>
需保证找到的这个方案总抢修时间最短。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">    输入文件有多组数据，第1行为 1 个整数t，为 case总数，接下来按顺序<br/>
给出每个case 描述，首先是两个整数 n，m（1≤n≤12, 1≤m≤40）分别表示<br/>
城市数量和公路数量，下面m行每行 3个整数x，y，c 描述了一条公路的情况：<br/>
x城市与y城市之间的一条公路，抢修该公路需要 c个单位时间。<br/>
注意上面所说的两城市间可能有多条公路。<br/>
</font></p></div>

# Output

<div class="content"><p><span style="font-size: medium">    按顺序输出每个 case 的结果，如果找不到一条合适的方案，则输出一行<br/>
“impossible”，否则输出一个整数，为抢修的最优方案所需要的总时间。<br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4 6<br/>
1 2 1<br/>
1 3 2<br/>
1 3 3<br/>
2 4 2<br/>
3 4 1<br/>
2 3 1<br/>
2 1<br/>
1 2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
impossible</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">陕西省队选拔赛</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 HYF上传">鸣谢 HYF上传</a></p></div>

