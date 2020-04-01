
# Description

<div class="content"><div>Alice听说在一片神奇的大陆MagicLand，有一个古老的传说……很久很久以前，那个时候 MagicStates共和国刚刚</div>
<div>成立。 反对新政府的势力虽已被镇压，但仍然在暗地活动。这一次，情报局得到了一个令人震惊的消息，被软禁</div>
<div>在首都府邸中的Frank ——著名的反对派领袖，秘密逃出首都，去往反对派的大本营。根据相关的情报，Frank计</div>
<div>划通过城市之间 发达的高速公路，经过最短的路程抵达目的地。不妨将 MagicStates共和国简化为由N个城市,M条</div>
<div>高速公路构成的连通的无向图，首都为城市1，反对派的大本营为城市N。每条高速公路连接两个不同的城市，且路</div>
<div>程是已知的。而Frank选择了一条从城市1到城市N的最短路径作为他的逃跑路线。为了阻止Frank，共和国总统决定</div>
<div>在某些城市的高速公路的出入口设立检查 点，在Frank经过检查点时将他逮捕。举例来说，如果有一条高速公路连</div>
<div>接城市u和城市v，在这条公路的城市u或城市v的出入口设立检查点，那么Frank经过高速公路时就会被发现。特别</div>
<div>的是，由于城市N实际上处在反对派的控制下，所以不能在城市N设立检查点。然而在任何城市设立检查点都需要一</div>
<div>定的费用。更具体的，若在城市 u设立k个检查点，就要花费 Au乘以k的代价，其中Au是城市u的相关参数。值得注</div>
<div>意的是，这个代价与这k个检查点具体设在哪些公路的出入口无关,于是，总统责令情报局拟定一个方案，花费最小</div>
<div>的代价使得无论Frank选择哪条最短路线，都会在（除城市N以外）某个城市的高速公路出入口被发现。读到这里，</div>
<div>Alice很想知道阻止Frank所需要花费的最小代价，并且她还希 望知道最优方案是否是唯一的。只好再请你帮助她</div>
<div>了。注意，我们称两个方案不同当且仅当存在某城市k，两种方案中在城市 k的检查点的设置（而不仅是数目）是</div>
<div>不同的。 </div>
<div>注意，输入文件包含多组测试数据。</div></div>

# Input

<div class="content"><div>
<div>第一行包含一个正整数T，表示有T组测试数据。</div>
<div>接下来依次是T组测试数据。</div>
<div>每组测试数据的第一行包含两个整数N、M。</div>
<div>第二行包含N-1个正整数，依次表示A1，A2，…，An-1。</div>
<div>接下来M行，每行三个整数Ui,Vi,Ci,表示一条连接城市Ui和城市Vi的路程等于Ci的高速公路</div>
<div>2≤N≤400,1≤M≤4000，1≤T≤5，</div>
<div>1≤Ai,c≤10^9。无向图可能有重边。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出T行，依次表示每组测试数据的答案。</div>
<div>若最优方案唯一则输出”Yes”和最小代价，</div>
<div>否则输出”No”和最小代价。字符串和整数之间请用一个空格隔开。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
3  3<br/>
2  4<br/>
1  3 23<br/>
3  2 12<br/>
2  1 11<br/>
4  4<br/>
3  2 2<br/>
1  2 1<br/>
2  3 1<br/>
3  4 1<br/>
4  1 1<br/>
3  4<br/>
3  2<br/>
1  2 1<br/>
2  3 2<br/>
2  3 19<br/>
3  1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes 4 <br/>
Yes 3 <br/>
No 2 <br/>
//第1组测试数据：最优方案是在城市1 设立两个检查点。 <br/>
第2组测试数据：最优方案是城市1的高速公路( 1, 4)的出入口设立检查点。  <br/>
第3组测试数据：最优方案是在城市2设立一个检查点，不过既可以设置在<br/>
高速公路(1, 2)的出入口，也可以设置在高速公路(2, 3)的出入口。 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

