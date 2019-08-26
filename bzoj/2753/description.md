
# Description

<div class="content"><div><span style="font-size: medium">a180285非常喜欢滑雪。他来到一座雪山，这里分布着M条供滑行的轨道和N个轨道</span><span style="font-size: medium">之间的交点（同时也是景点），而且每个景点都有一编号i（1&lt;=i&lt;=N）和一高度Hi。a180285</span><span style="font-size: medium">能从景点i 滑到景点j 当且仅当存在一条i 和j 之间的边，且i 的高度不小于j。 </span><span style="font-size: medium">与其他滑雪爱好者不同，a180285喜欢用最短的滑行路径去访问尽量多的景点。如果仅</span><span style="font-size: medium">仅访问一条路径上的景点，他会觉得数量太少。于是a180285拿出了他随身携带的时间胶囊。</span><span style="font-size: medium">这是一种很神奇的药物，吃下之后可以立即回到上个经过的景点（不用移动也不被认为是</span><span style="font-size: medium">a180285 滑行的距离）。请注意，这种神奇的药物是可以连续食用的，即能够回到较长时间</span><span style="font-size: medium">之前到过的景点（比如上上个经过的景点和上上上个经过的景点）。 </span><span style="font-size: medium">现在，a180285站在1号景点望着山下的目标，心潮澎湃。他十分想知道在不考虑时间</span></div>
<div><span style="font-size: medium">胶囊消耗的情况下，以最短滑行距离滑到尽量多的景点的方案（即满足经过景点数最大的前</span><span style="font-size: medium">提下使得滑行总距离最小）。你能帮他求出最短距离和景点数吗？ </span></div>
<div></div></div>

# Input

<div class="content"><div><span style="font-size: medium">输入的第一行是两个整数N，M。 </span></div>
<div><span style="font-size: medium">接下来1行有N个整数Hi，分别表示每个景点的高度。 </span></div>
<div><span style="font-size: medium">接下来M行，表示各个景点之间轨道分布的情况。每行3个整数，Ui，Vi，Ki。表示</span></div>
<div><span style="font-size: medium">编号为Ui的景点和编号为Vi的景点之间有一条长度为Ki的轨道。 </span></div>
<div></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">输出一行，表示a180285最多能到达多少个景点，以及此时最短的滑行距离总和。 </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"> <br/>
3 3 <br/>
3 2 1 <br/>
1 2 1 <br/>
2 3 1 <br/>
1 3 10 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 2 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】 <br/><br/>
    对于30%的数据，保证 1&lt;=N&lt;=2000 <br/><br/>
    对于100%的数据，保证 1&lt;=N&lt;=100000 <br/><br/>
对于所有的数据，保证 1&lt;=M&lt;=1000000，1&lt;=Hi&lt;=1000000000，1&lt;=Ki&lt;=1000000000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

