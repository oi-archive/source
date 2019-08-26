
# Description

<div class="content"><div>Bob有一棵n个点的有根树，其中1号点是根节点。Bob在每个点上涂了颜色，并且每个点上的颜色不同。定义一条路</div>
<div>径的权值是：这条路径上的点（包括起点和终点）共有多少种不同的颜色。Bob可能会进行这几种操作：</div>
<div>1 x:</div>
<div>把点x到根节点的路径上所有的点染上一种没有用过的新颜色。</div>
<div>2 x y:</div>
<div>求x到y的路径的权值。</div>
<div>3 x</div>
<div>在以x为根的子树中选择一个点，使得这个点到根节点的路径权值最大，求最大权值。</div>
<div>Bob一共会进行m次操作</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个数n,m。</div>
<div>接下来n-1行，每行两个数a,b，表示a与b之间有一条边。</div>
<div>接下来m行，表示操作，格式见题目描述</div>
<div>1&lt;=n,m&lt;=100000</div>
<div></div></div>

# Output

<div class="content"><div>每当出现2,3操作，输出一行。</div>
<div>如果是2操作，输出一个数表示路径的权值</div>
<div>如果是3操作，输出一个数表示权值的最大值</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
1 2<br/>
2 3<br/>
3 4<br/>
3 5<br/>
2 4 5<br/>
3 3<br/>
1 4<br/>
2 4 5<br/>
1 5<br/>
2 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
2<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢infinityedge上传">鸣谢infinityedge上传</a></p></div>

