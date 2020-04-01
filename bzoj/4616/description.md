
# Description

<div class="content"><div>有一些城市，你知道连接每一对城市之间的路的长度，而且路都是单向的。每条路都有固定的30码至60码的限速（</div>
<div>可以是小数）。运输货车一定会沿着最短路行进，而且在每条路上会始终以最高限速行驶。因此，在不知道其余信</div>
<div>息的情况下，如果一次行程长度为50km，则它需要花的时间在50至100分钟之间。但是你有其余的信息--例如之前</div>
<div>的行程所花的时间。请使用这些信息给出最准确的估算。</div></div>

# Input

<div class="content"><div>
<div>第一行一个数n(1 ≤ n ≤ 30)，表示城市数量。城市从0标号到n-1。</div>
<div>之后n行，每行n个数，表示城市之间的路程长度：第i行第j个数表示从城市i到城市j的直接距离（km），-1表示没</div>
<div>有道路直接连接这两个城市。城市到自己的距离一定是0；其它的距离都为正数且不超过1000。最多只会有100条路</div>
<div>。</div>
<div>接下来一行一个数r(1 ≤ r ≤ 100)表示已经运送过的路线数量。</div>
<div>接下来r行，每行三个整数s、d、t，表示从城市s到城市d花了t分钟。</div>
<div>最后一行一个数q(1 ≤ q ≤ 100)表示询问数量。</div>
<div>接下来q行每行2个数s和d表示运送的起始地点和目的地。</div>
<div>你可以认为这r+q对起始地点和目的地之间都有一条唯一的最短路径。</div>
</div></div>

# Output

<div class="content"><div>对于每个询问输出一行，先输出该询问的起始地点和目的地</div>
<div>然后输出估计行程时间的最小值和最大值，绝对或相对误差在1e-6以内算作正确。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 50 -1<br/>
55 0 40<br/>
-1 40 0<br/>
1<br/>
0 2 90<br/>
3<br/>
0 1<br/>
1 2<br/>
1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 1 50.0 80.0<br/>
1 2 40.0 70.0<br/>
1 0 55.0 110.0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Shimakaze提供译文">鸣谢Shimakaze提供译文</a></p></div>

