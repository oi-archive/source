
# Description

<div class="content"><p></p>
<div>有一棵n个节点的无根树，节点编号为1..n。每个节点有一个非负权值。现在需要把这棵树分成若干个联通块（不</div>
<div>能有剩下的点），每个联通块的节点个数在k1和k2之间，每个联通块的得分就是该联通块中所有节点权值的平均值</div>
<div>。总得分就是指对这个树切割后所有联通块的得分的和。你需要求出一种分割的方案使得总得分尽量小。</div></div>

# Input

<div class="content"><div>第一行三个整数n,k1,k2，1≤k1≤k2≤n，2≤n≤50；</div>
<div>第二行n个整数，第i个数表示编号为i的节点的权值，每两个相邻整数之间用一个空格隔开；</div>
<div>接下来n-1行，每行两个整数x,y，表示编号为x的节点和编号为y的节点之间有一条边。</div></div>

# Output

<div class="content"><div>如果存在一个切割方案，那么输出一个实数(四舍五入保留二位小数)，表示所有分割方案中最小的总得分。如果不</div>
<div>存在切割方案，那么输出所有节点权值和的两倍。如果对于某个测试点你的输出和标准输出完全一样，那么将得到</div>
<div>该测试点全部的分，否则该测试点不得分（我的sp貌似有问题，大家可以使用double类型存储数据，输出结果的整</div>
<div>数部分保证不超过9位（十进制），使用double类型可以保证小数部分至少是6位，因而精度应该不存在问题）。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 1 1<br/>
1 1 1<br/>
1 2<br/>
2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3.00<br/>
【数据规模】<br/>
对于100%的数据，n&lt;=50，每个点的权值不超过10^9。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

