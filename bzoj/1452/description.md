
# Description

<div class="content"><div>一个N*M的方格，初始时每个格子有一个整数权值，接下来每次有2个操作:</div>
<div>改变一个格子的权值</div>
<div>求一个子矩阵中某个特定权值出现的个数</div>
<div></div></div>

# Input

<div class="content"><div>每一行有两个数字N，M</div>
<div>接下来N行，每行M个数字。第i+1行第j个数字表示格子(i,j)的初值</div>
<div>接下来输入一个Q，后面Q行每行描述一个操作</div>
<div>操作1:</div>
<div>1 x y c，表示将格子(x,y)的值变为c</div>
<div>操作2:</div>
<div>2 x1 x2 y1 y2 c，表示询问所有满足格子中数字为c的格子数字</div>
<div>(n,m&lt;=300,Q&lt;=5000)</div>
<div>(1&lt;=x&lt;=N,1&lt;=y&lt;=M,1&lt;=c&lt;=100)</div>
<div>(x1&lt;=x&lt;=x2,y1&lt;=y&lt;=y2)</div></div>

# Output

<div class="content"><p>对于每个操作2,按输入中出现的顺序，依次输出一行一个整数表示所求得的个数</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 3<br/>
3 2 1<br/>
2 1 3<br/>
3<br/>
2 1 2 1 2 1<br/>
1 2 3 2<br/>
2 2 3 2 3 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

