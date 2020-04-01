
# Description

<div class="content"><div>小y有n个妹子，编号分别为1, 2，... n。为了更好管理这些妹子，小y想把他们分成若干组～</div>
<div></div>
<div>在开始的开始（我们记作分组方案0）中，每个妹子各成一组。</div>
<div>每次小y会选择一个已有的分组方案i，挑出其中两个不在同组的妹子x, y，将她们所在的组合并。</div>
<div>我们将第j次操作得到的分组方案记作分组方案j。这样就可以得到许多不同的分组方案啦！</div>
<div></div>
<div></div>
<div>为了知道这些分组方案孰优孰劣，因此小y想知道关于分组方案的一些信息。</div>
<div>每次，小y会选择某一个分组方案i，询问x所在的组中编号第k小的妹子是谁。</div>
<div></div>
<div></div>
<div>为了小y的幸福（划掉），来帮帮他把（逃</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n, m。表示妹子数和操作数。</div>
<div>接下来的m行，首先有一个整数opt。</div>
<div>如果opt=0，接下来三个整数i, x, y，表示一次合并。保证分组方案i已经出现过，x, y在不同组中。</div>
<div>如果opt=1，接下来三个整数i, x, k，表示一次询问。保证x所在的组中至少有k个妹子。</div>
<div>1 &lt;=n, q &lt;= 100000，合并不超过60000次，询问不超过60000次</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问操作输出一个整数，表示该妹子的编号</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 6<br/>
0 0 1 2<br/>
1 1 1 2<br/>
1 1 2 1<br/>
0 1 2 3<br/>
0 1 1 3<br/>
1 3 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Awd上传">Awd上传</a></p></div>

