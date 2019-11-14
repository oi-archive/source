
# Description

<div class="content"><div>星之卡比的地图是一个由N个点组成的树，每个节点拥有一个荣誉值。游戏设定了M个子任务，对应了树上的M条路</div>
<div>径。每个子任务也有一个荣誉值，等于这条路径上所有节点的荣誉值之积。小F决定设计一些任务列表，每个任务</div>
<div>列表包含K个子任务，玩家需要依次完成这些子任务。一个任务列表中允许包含多个相同的子任务，但必须满足：</div>
<div>1.任意两个子任务的荣誉值之积都为完全平方数。</div>
<div>2.不存在P(P&gt;1)，使得任务列表能被分成长度相等的P段，且这P段完全相同。（老是玩同样模式的子任务很容易就无聊啦。。。）</div>
<div>现在的小F想知道，当K分别等于1..M的时候，他能够设计多少种任务列表呢？</div>
<div>由于答案可能很大，所以对输出的答案mod 1000000007。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个数N和M</div>
<div>第二行包含N个数，依次表示每个节点的荣誉值</div>
<div>接下来N-1行，每行两个数x、y，描述一条连接节点x与y的边</div>
<div>接下来M行，每行两个数x、y，描述一个子任务为树上x到y的路径</div>
<div>N,M≤2000,所有输入数据都为不超过10^5的正整数，保证输入数据合法</div>
<p></p></div>

# Output

<div class="content"><div>包含M个数，分别表示K=1..M的时候，能够设计的任务列表的种类数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
2 2 2 2 3<br/>
1 2<br/>
1 3<br/>
3 4<br/>
3 5<br/>
2 4<br/>
1 5<br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 2 6<br/>
<br/>
样例解释<br/>
子任务1、2、3的荣誉值分别为16、12、12<br/>
K=1，任务列表为{1} {2} {3}<br/>
K=2，任务列表为{2,3} {3,2}<br/>
K=3，任务列表为{2,2,3} {2,3,2} {2,3,3} {3,2,2} {3,2,3} {3,3,2}</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

