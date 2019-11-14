
# Description

<div class="content"><div>给定一个n个点的树，每个点的编号从1至n，问这个树有多少不同的连通子树，和这个树有相同的重心。</div>
<div>其中n个点的树指的是n个点的最小连通图，显然n个点的树有n-1条边，去掉这n-1条边中的任何一条，原图都不再联通，任意两个点之间由唯一一条路径相连。</div>
<div>对于一个树，树的重心定义为：删掉某点i后，若剩余k个连通分量，那么定义d(i)为这些连通分量中点的个数的最大值，所谓重心，就是使得d(i)最小的点i。</div>
<div>基于以上定义，一个树的重心可能会有一个或者两个，题中所要求的联通子树，其重心编号和个数必须和原树的完全一样。</div>
<div>找出给定的树中有多少联通的子树和这个树有相同的重心。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行中给出正整数Q，表示该组数据中有多少组测试样例。</div>
<div>
<div>每组样例首先输入一个整数n (0 &lt; n ≤200)，表示该组样例中输入的树包含n个点，之后n-1行，每行输入两整数数x，y(1 ≤ x, y ≤ n)，表示编号为x的点和编号为y的点之间存在一条边，所有点的编号从1-n</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>首先输出样例编号，之后输出满足条件的子树的个数，由于这个数字较大，你只需要输出这个数字对10007取模后的结果，即mod 10007，详见输出示例，请严格按照输出实例中的格式输出</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2<br/>
1 2<br/>
3<br/>
1 2<br/>
2 3<br/>
5<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 1<br/>
Case 2: 2<br/>
Case 3: 6</span></div>

# Hint

<div class="content"><p></p><p>100%的数据满足Q≤50，n≤200。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

