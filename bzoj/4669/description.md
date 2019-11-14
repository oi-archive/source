
# Description

<div class="content"><div>大战将至, 美国决定实行计划经济。美国西部总共有 N 个城市，编号</div>
<div>为 0 ∼ N − 1，以及 M 条道路，道路是单向的。其中城市 0 是一个大城</div>
<div>市，里面住着 K 个人，而城市 N − 1 是一个农业城市。现在所有城市 0 的</div>
<div>居民都需要到城市 N − 1 去领取食物。由于担心体力不支，所以居民都会</div>
<div>采取开车的形式出行。但道路不是无限宽的，对于一条道路，会有 ci 的限</div>
<div>制，表示在同一天内，最多只能有 ci 辆车同时在这条道路上行驶。一条道</div>
<div>路的长度为 1，每辆车的行驶速度也可以假定为 1 每天。城市 N − 1 会在</div>
<div>每个居民都到达后马上开始发放食物。现在 Reddington 想知道，假如在最</div>
<div>优安排下，居民最早能在多少天后领到食物。假如没有居民那就不需要发</div>
<div>放食物，默认为第 0 天。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>一个测试点包含多组数据。</div>
<div>对于每组数据：</div>
<div>第一行包括三个整数 N, M, K。</div>
<div>接下来 M 行，每行三个整数 u, v, c，描述一条从 u 出发到 v 的道路。</div>
<div>1 ≤ N ≤ 1000, 1 ≤ M ≤ 5000, 0 ≤ K ≤10^9</div>
<div>0 ≤ u, v &lt; N, 1 ≤ ci ≤ 109，数据组数不超过 10 组</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，</div>
<div>假如无解，输出”No solution”，不包括引号。</div>
<div>假如有解，输出最早的天数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 6 4 <br/>
0 1 2<br/>
0 3 1<br/>
1 2 1<br/>
2 3 1<br/>
1 4 1<br/>
3 4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
//第 1， 2 个人都选择第 0 天开始出发，分别走 0-1-4， 0-3-4 的道路，第<br/>
3,4 个人从第 1 天开始出发，沿着前两个人的路线走。总共只需要 3 天。可<br/>
以证明这是最优解。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

