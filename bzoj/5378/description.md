
# Description

<div class="content"><div>给定一个n个点m条边的带权图，每条边的边权为 wi，有两种询问。</div>
<div>1.求其最小方差生成树。</div>
<div>2.对于每条边，问如果删除它，残余图（包含 n 个点 m-1 条边）的最小方差生成树。</div>
<div>你只需要求出最小的方差值。如果图不连通，输出 -1。</div>
<div>一个生成树的方差定义为它的所有边的权值的方差。</div>
<div>对于N个变量 X1,X2...XN。其方差计算方式为σ^2=(∑1≤i≤N (xi-μ)^2)/N</div>
<div>​其中σ^2为方差,μ为平均值，由于是生成树，所以N=n-1。</div>
<div>你需要将方差乘N^2后输出，可以证明这是一个整数。</div>
<p></p></div>

# Input

<div class="content"><div>第1行包含3个整数n,m,T，表示点数，边数和询问类型。</div>
<div>接下来m行，每行包含3个正整数ui,vi,wi，表示第i条边连接ui和vi，权值为wi，</div>
<div>保证无自环，但可能有重边。</div>
<div>m≤100000，n≤m，C≤ 1e^18</div>
<p></p></div>

# Output

<div class="content"><div>当 T=1，输出一个数表示答案。</div>
<div>当 T=2，输出 m 行，每行一个数表示删除第 i 条边的答案。</div>
<div>如果图不连通，输出-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 2<br/>
1 2 1<br/>
2 3 3<br/>
1 3 2<br/>
3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
26<br/>
24<br/>
-1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

