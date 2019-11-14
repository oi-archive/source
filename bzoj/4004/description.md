
# Description

<div class="content"><div>脸哥最近在玩一款神奇的游戏，这个游戏里有 n 件装备，每件装备有 m 个属性，用向量zi(aj ,.....,am) 表示 </div>
<div>(1 &lt;= i &lt;= n; 1 &lt;= j &lt;= m)，每个装备需要花费 ci，现在脸哥想买一些装备，但是脸哥很穷，所以总是盘算着</div>
<div>怎样才能花尽量少的钱买尽量多的装备。对于脸哥来说，如果一件装备的属性能用购买的其他装备组合出（也就是</div>
<div>说脸哥可以利用手上的这些装备组合出这件装备的效果），那么这件装备就没有买的必要了。严格的定义是，如果</div>
<div>脸哥买了 zi1,.....zip这 p 件装备，那么对于任意待决定的 zh，不存在 b1,....,bp 使得 b1zi1 + ... + bpzi</div>
<div>p = zh（b 是实数），那么脸哥就会买 zh，否则 zh 对脸哥就是无用的了，自然不必购买。举个例子,z1 =(1; 2;</div>
<div> 3);z2 =(3; 4; 5);zh =(2; 3; 4)，b1 =1/2，b2 =1/2，就有 b1z1 + b2z2 = zh，那么如果脸哥买了 z1 和 z2 </div>
<div>就不会再买 zh 了。脸哥想要在买下最多数量的装备的情况下花最少的钱，你能帮他算一下吗？</div></div>

# Input

<div class="content"><div>第一行两个数 n;m。接下来 n 行，每行 m 个数，其中第 i 行描述装备 i 的各项属性值。接下来一行 n 个数，</div>
<div>其中 ci 表示购买第 i 件装备的花费。</div></div>

# Output

<div class="content"><p>一行两个数，第一个数表示能够购买的最多装备数量，第二个数表示在购买最多数量的装备的情况下的最小花费</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 3<br/>
3 4 5<br/>
2 3 4<br/>
1 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 2</span></div>

# Hint

<div class="content"><p></p><div>如题目中描述，选择装备 1 装备 2，装备 1 装备 3，装备 2 装备 3 均可，但选择装备 1 和装备 2 的花费最小，为 2。对于 100% 的数据, 1 &lt;= n;m &lt;= 500; 0 &lt;= aj &lt;= 1000。</div><br/>
<div>新加数据三组--2016.5.13</div><br/>
<div></div><br/>
<div></div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

