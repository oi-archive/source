
# Description

<div class="content"><div>有一条长度为n的链（1≤i&lt;n，点i与点i+1之间有一条边的无向图），每个点有一个整数权值，第i个点的权值是</div>
<div>a_i。现在有m个操作，每个操作如下：</div>
<div></div>
<div>操作1（修改）：给定链上两个节点u、v和一个整数d，表示将链上u到v唯一的简单路径上每个点权值都加上d。</div>
<div></div>
<div>操作2（询问）：给定两个正整数L、r，表示求链上所有节点个数大于等于L且小于等于r的简单路径节点权值和之和。</div>
<div></div>
<div>由于答案很大，只用输出对质数1000000007取模的结果即可。</div>
<div>一条节点个数为k的简单路径节点权值和为这条上所有k个节点（包括端点）的权值之和，</div>
<div>而本题中要求是对所有满足要求的简单路径，求这一权值和的和。</div>
<div>由于是无向图，路径也是无向的，即点1到点2的路径与点2到点1的路径是同一条，不要重复计算。</div></div>

# Input

<div class="content"><div>输入第一行包含两个正整数n、m，分别表示节点个数和操作次数。</div>
<div>第二行包含n个整数，其中第ii个数ai为第ii个点的初始权值。</div>
<div>接下来m行，每行为1 u v d或2 l r的形式，分别表示进行一次操作1（修改）或操作2（询问）。</div>
<div>记操作 1（修改）的次数为 m</div>
<div>n &lt;= 200000, </div>
<div>m &lt;= 500000, </div>
<div>m&#39;&lt;= 100000, </div>
<div>0 &lt;= a_i &lt;1000000007</div>
<div>1 &lt;= u &lt;= n</div>
<div>1&lt;= v &lt;= n </div>
<div>0 &lt;= d &lt; 1000000007</div>
<div>l &lt;= r &lt;= n</div></div>

# Output

<div class="content"><div>对于每次询问，输出一行一个整数，表示答案对1000000007取模的余数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 1 1 1 1<br/>
2 5 5<br/>
2 1 2<br/>
1 1 2 2<br/>
2 1 1<br/>
1 1 5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
13<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

