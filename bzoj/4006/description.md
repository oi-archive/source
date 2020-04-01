
# Description

<div class="content"><p>小铭铭最近进入了某情报部门，该部门正在被如何建立安全的通道连接困扰。</p>
<div>该部门有 n 个情报站，用 1 到 n 的整数编号。给出 m 对情报站 ui;vi 和费用 wi，表示情</div>
<div>报站 ui 和 vi 之间可以花费 wi 单位资源建立通道。</div>
<div>如果一个情报站经过若干个建立好的通道可以到达另外一个情报站，那么这两个情报站就</div>
<div>建立了通道连接。形式化地，若 ui 和 vi 建立了通道，那么它们建立了通道连接；若 ui 和 vi 均</div>
<div>与 ti 建立了通道连接，那么 ui 和 vi 也建立了通道连接。</div>
<div>现在在所有的情报站中，有 p 个重要情报站，其中每个情报站有一个特定的频道。小铭铭</div>
<div>面临的问题是，需要花费最少的资源，使得任意相同频道的情报站之间都建立通道连接。</div></div>

# Input

<div class="content"><p>第一行包含三个整数 n;m;p，表示情报站的数量，可以建立的通道数量和重要情报站的数</p>
<div>量。接下来 m 行，每行包含三个整数 ui;vi;wi，表示可以建立的通道。最后有 p 行，每行包含</div>
<div>两个整数 ci;di，表示重要情报站的频道和情报站的编号。</div></div>

# Output

<div class="content"><p>输出一行一个整数，表示任意相同频道的情报站之间都建立通道连接所花费的最少资源总量。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8 4<br/>
1 2 3<br/>
1 3 2 <br/>
1 5 1<br/>
2 4 2<br/>
2 5 1<br/>
3 4 3 <br/>
3 5 1<br/>
4 5 1<br/>
1 1<br/>
1 2<br/>
2 3<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p>选择 (1; 5); (3; 5); (2; 5); (4; 5) 这 4 对情报站连接。</p><br/>
<div>对于 100% 的数据，0 &lt;ci &lt;= p &lt;= 10; 0 &lt;ui;vi;di &lt;= n &lt;= 1000; 0 &lt;= m &lt;= 3000; 0 &lt;= wi &lt;=</div><br/>
<div>20000。</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

