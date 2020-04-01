
# Description

<div class="content"><div>&#34;奋战三星期，造台计算机&#34;。小G响应号召，花了三小时造了台普通计算姬。普通计算姬比普通计算机要厉害一些</div>
<div>。普通计算机能计算数列区间和，而普通计算姬能计算树中子树和。更具体地，小G的计算姬可以解决这么个问题</div>
<div>：给定一棵n个节点的带权树，节点编号为1到n，以root为根，设sum[p]表示以点p为根的这棵子树中所有节点的权</div>
<div>值和。计算姬支持下列两种操作:</div>
<div>1 给定两个整数u,v，修改点u的权值为v。</div>
<div>2 给定两个整数l,r，计算sum[l]+sum[l+1]+....+sum[r-1]+sum[r]</div>
<div>尽管计算姬可以很快完成这个问题，可是小G并不知道它的答案是否正确，你能帮助他吗？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,m，表示树的节点数与操作次数。</div>
<div>接下来一行n个整数，第i个整数di表示点i的初始权值。</div>
<div>接下来n行每行两个整数ai,bi，表示一条树上的边，若ai=0则说明bi是根。</div>
<div>接下来m行每行三个整数，第一个整数op表示操作类型。</div>
<div>若op=1则接下来两个整数u,v表示将点u的权值修改为v。</div>
<div>若op=2则接下来两个整数l,r表示询问。</div>
<div>N&lt;=10^5,M&lt;=10^5</div>
<div>0&lt;=Di,V&lt;2^31,1&lt;=L&lt;=R&lt;=N,1&lt;=U&lt;=N</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对每个操作类型2输出一行一个整数表示答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4<br/>
0 0 3 4 0 1<br/>
0 1<br/>
1 2<br/>
2 3<br/>
2 4<br/>
3 5<br/>
5 6<br/>
2 1 2<br/>
1 1 1<br/>
2 3 6<br/>
2 3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">16<br/>
10<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

