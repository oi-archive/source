
# Description

<div class="content"><div>
<div>小凸和小方相约玩密室逃脱，这个密室是一棵有n个节点的完全二叉树，每个节点有一个灯泡。点亮所有灯泡即可</div>
<div>逃出密室。每个灯泡有个权值Ai，每条边也有个权值bi。点亮第1个灯泡不需要花费，之后每点亮1个新的灯泡V的</div>
<div>花费，等于上一个被点亮的灯泡U到这个点V的距离Du,v，乘以这个点的权值Av。在点灯的过程中，要保证任意时刻</div>
<div>所有被点亮的灯泡必须连通，在点亮一个灯泡后必须先点亮其子树所有灯泡才能点亮其他灯泡。</div>
<div>请告诉他们，逃出密室的最少花费是多少。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第1行包含1个数n，代表节点的个数</div>
<div>第2行包含n个数，代表每个节点的权值ai。(i=l，2，…，n)</div>
<div>第3行包含n-l个数，代表每条边的权值bi，第i号边是由第(i+1)/2号点连向第i+l号点的边。</div>
<div>(i=l，2...N-1)</div>
<p></p></div>

# Output

<div class="content"><div>输出包含1个数，代表最少的花费。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
5 1 2<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1≤N≤2×105，1&lt;Ai,Bi≤10^5</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

