
# Description

<div class="content"><div>master 对树上的求和非常感兴趣。他生成了一棵有根树，并且希望多次询问这棵树上一段路径上所有节点深度的k</div>
<div> 次方和，而且每次的k 可能是不同的。此处节点深度的定义是这个节点到根的路径上的边数。他把这个问题交给</div>
<div>了pupil，但pupil 并不会这么复杂的操作，你能帮他解决吗？</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n ，表示树的节点数。</div>
<div>之后n-1 行每行两个空格隔开的正整数i,j ，表示树上的一条连接点i 和点j 的边。</div>
<div>之后一行一个正整数m ，表示询问的数量。</div>
<div>之后每行三个空格隔开的正整数i,j,k ，表示询问从点i 到点j 的路径上所有节点深度的k 次方和。</div>
<div>由于这个结果可能非常大，输出其对998244353 取模的结果。</div>
<div>树的节点从1 开始标号，其中1 号节点为树的根。</div>
<div></div></div>

# Output

<div class="content"><div>对于每组数据输出一行一个正整数表示取模后的结果。</div>
<div>1≤n,m≤300000,1≤k≤50</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
2<br/>
1 4 5<br/>
5 4 45</span></div>

# Sample Output

<div class="content"><span class="sampledata">33<br/>
503245989<br/>
说明<br/>
样例解释<br/>
以下用d(i) 表示第i 个节点的深度。<br/>
对于样例中的树，有d(1)=0,d(2)=1,d(3)=1,d(4)=2,d(5)=2。<br/>
因此第一个询问答案为(2^5 + 1^5 + 0^5) mod 998244353 = 33 <br/>
第二个询问答案为(2^45 + 1^45 + 2^45) mod 998244353 = 503245989。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

