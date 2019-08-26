
# Description

<div class="content"><div>一个公司的组织领导架构可以用一棵领导树来表示。公司的每个成员对应于树中一个结点 v_i，且每个成员都有响</div>
<div>应的级别 w_i。越高层的领导，其级别值 w_i 越小。树中任何两个结点之间有边相连，则表示与结点相应的两个</div>
<div>成员属于同一部门。领导集团问题就是根据公司的领导树确定公司的最大部门。换句话说，也就是在领导树中寻找</div>
<div>最大的部门结点子集，使得的结点 v_i 和 v_j，如果 v_i 是 v_j 的子孙结点，则 w_i &gt;= w_j。</div>
<div>编程任务：对于任意对于给定的领导树，计算出领导树中最大的部门结点子集。</div>
<p></p></div>

# Input

<div class="content"><div>第一行有一个正整数 n，表示领导树的结点数。</div>
<div>接下来的一行中有 n 个整数。第 i 个数表示 w_i。</div>
<div>再接下来的 n-1 行中，第 i 行有一个整数 v_i 表示 v_i 是 i+1 的双亲结点。</div>
<div>n 为正整数，n &lt;= 200000，0 &lt; w_i &lt;= 10^9。</div>
<p></p></div>

# Output

<div class="content"><div>输出找到的最大的部门的成员数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2 5 1 3 5 4<br/>
1<br/>
1<br/>
2<br/>
2<br/>
4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Qingyu上传">鸣谢Qingyu上传</a></p></div>

