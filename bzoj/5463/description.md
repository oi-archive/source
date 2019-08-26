
# Description

<div class="content"><div>比特镇的路网由 m 条双向道路连接的 n 个交叉路口组成。</div>
<div></div>
<div>最近，比特镇获得了一场铁人两项锦标赛的主办权。这场比赛共有两段赛程：选手先完成一段长跑赛程，然后骑自行车完成第二段赛程。</div>
<div></div>
<div>比赛的路线要按照如下方法规划：</div>
<div></div>
<div>1、先选择三个两两互不相同的路口 s， c 和 f ，分别作为比赛的起点、切换点（运动员在长跑到达这个点后，骑自行车前往终点）、终点。</div>
<div></div>
<div>2、选择一条从 s 出发，经过 c 最终到达 f 的路径。考虑到安全因素，选择的路径经过同一个点至多一次。</div>
<div></div>
<div>在规划路径之前，镇长想请你帮忙计算，总共有多少种不同的选取 s， c 和 f 的方案，使得在第 2 步中至少能设计出一条满足要求的路径。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数 n 和 m ，分别表示交叉路口和双向道路的数量。</div>
<div>接下来 m 行，每行两个整数 v_i， u_i 。表示存在一条双向道路连接交叉路口 v_i， u_i (1 &lt;= v_i, u_i &lt;= n, v_i != u_i)。</div>
<div>保证任意两个交叉路口之间，至多被一条双向道路直接连接。</div>
<div>n&lt;=1e5, m&lt;=2e5</div>
<p></p></div>

# Output

<div class="content"><div>输出一行，包含一个整数，表示能满足要求的不同的选取s,c和f的方案数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2<br/>
2 3<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Qingyu上传">鸣谢Qingyu上传</a></p></div>

