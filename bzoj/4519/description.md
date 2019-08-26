
# Description

<div class="content"><div>学过图论的同学都知道最小割的概念：对于一个图，某个对图中结点的划分将图中所有结点分成</div>
<div>两个部分，如果结点s,t不在同一个部分中，则称这个划分是关于s,t的割。对于带权图来说，将</div>
<div>所有顶点处在不同部分的边的权值相加所得到的值定义为这个割的容量，而s,t的最小割指的是在</div>
<div>关于s,t的割中容量最小的割。</div>
<div>而对冲刺NOI竞赛的选手而言，求带权图中两点的最小割已经不是什么难事了。我们可以把</div>
<div>视野放宽，考虑有N个点的无向连通图中所有点对的最小割的容量，共能得到N(N−1)</div>
<div>2个数值。</div>
<div>这些数值中互不相同的有多少个呢？这似乎是个有趣的问题。</div>
<div></div></div>

# Input

<div class="content"><div>输入文件第一行包含两个数N，M，表示点数和边数。接下来M行，每行三个数u，v，w，</div>
<div>表示点u和点v（从1开始标号）之间有条边权值是w。</div>
<div>1&lt;=N&lt;=850 1&lt;=M&lt;=8500 1&lt;=W&lt;=100000</div>
<div></div></div>

# Output

<div class="content"><p> 输出文件第一行为一个整数，表示个数。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 3<br/>
1 3 6<br/>
2 4 5<br/>
3 4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

