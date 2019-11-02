# 

 
 # 题目描述 
<p>RMQ问题与LCA问题基础<br />
一、RMQ问题<br />
RMQ问题&nbsp;(Range&nbsp;Minimum/Maximum&nbsp;Query)，首先给出一个序列，然后不断询问某个区间内的最大值和最小值。显然，我们在回答所有询问之前，需要根据序列进行一定的预处理。<br />
一种算法是采用线段树，即在线段树的每个节点保存该区间的最大值与最小值，O(n)的预处理时间（需要自底向上构建），可以O(logn)地回答每个问题。<br />
另一种算法就是神奇的ST算法（Sparse&nbsp;Table）&nbsp;，以求最大值为例，设v[n][f]表示[n,n+2^f)这个区间内的最大值，那么在询问到[a,b)区间的最大值时答案就是max(v[a][f],v[b-2^f][f])，其中f是满足2^f&lt;=b-a的最大的f。至于那张稀疏表，可以用递推的方法在O(nlogn)（也就是表的元素数）的时间内构建。也就是说v[n][f]=max(v[n][f-1],v[n+2^(f-1)][f])。<br />
另外，RMQ问题与LCA（Least&nbsp;Common&nbsp;Ancestors，最近公共祖先）问题可以互相转化。LCA问题有一个经典的离线算法Tarjan算法。<br />
ST算法O(nlogn)预处理,O(1)的查询指定区间的最值(以最小值为例)<br />
基本上是把待求区间[l,r]分为两段长为len的区间<br />
左边一段为[l,l+len-1],右边一段为[r-len+1,r]<br />
len必须使得两段区间覆盖待求区间<br />
设所求数组为w<br />
那么,所求最小值就是两个区间的最小值间的最小值<br />
即min(min{w[i],l&lt;=i&lt;=l+len-1},min{w[j],r-len+1&lt;=j&lt;=r})<br />
若都在预先处理中先求得两个区间的最小值<br />
则每次查询的复杂度都是O(1)<br />
---<br />
对len做一个限制:只能为2的幂<br />
在预处理中求出所有mi[b][t]&nbsp;:&nbsp;以b为起点,长为2^t的区间的最小值.<br />
则求解min(min{w[i],l&lt;=i&lt;=l+len-1},min{w[j],r-len+1&lt;=j&lt;=r})<br />
就变成min(mi[l][t],mi[r-2^t+1][r]),其中t可以由此得出,以保证两段区间可以覆盖待求区间:<br />
t=ln(r-l+1)/ln(2)<br />
---<br />
可以看到mi[b][t]=min(mi[b][t-1],mi[b+2^(t-1)-1][t-1])<br />
特别地对于所有mi[i][0],其值都是w[i];<br />
由此自底向上推出所有的mi[b][t]<br />
mi大小为n*logn,预处理时间复杂度为O(nlogn),查询时间复杂度为O(1)<br />
<br />
<br />
#include&nbsp;<iostream><br />
#include&nbsp;<math.h><br />
#define&nbsp;max(a,b)&nbsp;((a&gt;b)?a:b)<br />
#define&nbsp;min(a,b)&nbsp;(a<b?a:b) br=""><br />
using&nbsp;namespace&nbsp;std;<br />
<br />
const&nbsp;int&nbsp;maxn=50001;<br />
int&nbsp;h[maxn];<br />
int&nbsp;mx[maxn][16],mn[maxn][16];<br />
int&nbsp;n,q;<br />
<br />
void&nbsp;rmq_init()<br />
{<br />
int&nbsp;i,j;<br />
for(j=1;j&lt;=n;j++)&nbsp;mx[j][0]=mn[j][0]=h[j];<br />
int&nbsp;m=floor(log((double)n)/log(2.0));<br />
for(i=1;i&lt;=m;i++){<br />
for(j=n;j&gt;0;j--){<br />
mx[j][i]=mx[j][i-1];<br />
if(j+(1&lt;&lt;(i-1))&lt;=n)&nbsp;mx[j][i]=max(mx[j][i],mx[j+(1&lt;&lt;(i-1))][i-1]);<br />
}<br />
}<br />
for(i=1;i&lt;=m;i++){<br />
for(j=n;j&gt;0;j--){<br />
mn[j][i]=mn[j][i-1];<br />
if(j+(1&lt;&lt;(i-1))&lt;=n)&nbsp;mn[j][i]=min(mn[j][i],mn[j+(1&lt;&lt;(i-1))][i-1]);<br />
}<br />
}<br />
}<br />
<br />
int&nbsp;rmq(int&nbsp;l,int&nbsp;r)<br />
{<br />
int&nbsp;m=floor(log((double)(r-l+1))/log(2.0));<br />
int&nbsp;a=max(mx[l][m],mx[r-(1&lt;<m)+1][m]); br="">&nbsp;int&nbsp;b=min(mn[l][m],mn[r-(1&lt;<m)+1][m]); br="">&nbsp;return&nbsp;a-b;<br />
}<br />
<br />
int&nbsp;main()<br />
{<br />
int&nbsp;i,l,r;<br />
scanf(&quot;%d%d&quot;,&amp;n,&amp;q);<br />
for(i=1;i&lt;=n;i++)&nbsp;scanf(&quot;%d&quot;,&amp;h[i]);<br />
rmq_init();<br />
for(i=0;i<q;i++){ br="">&nbsp;scanf(&quot;%d%d&quot;,&amp;l,&amp;r);<br />
printf(&quot;%d\n&quot;,rmq(l,r));<br />
}<br />
}<br />
<br />
题目：USACO&nbsp;Jan07&nbsp;Gold&nbsp;lineupg<br />
POI&nbsp;2364<br />
<br />
二、LCA问题<br />
对于有根树T的两个结点u、v，最近公共祖先LCA(T,u,v)表示一个结点x，满足x是u、v的祖先且x的深度尽可能大。另一种理解方式是把T理解为一个无向无环图，而LCA(T,u,v)即u到v的最短路上深度最小的点。<br />
这里给出一个LCA的例子：<br />
例一<br />
对于T=<v,e><br />
V={1,2,3,4,5}<br />
E={(1,2),(1,3),(3,4),(3,5)}<br />
则有：<br />
LCA(T,5,2)=1<br />
LCA(T,3,4)=3<br />
LCA(T,4,5)=3<br />
<br />
<br />
<br />
(1)<br />
/&nbsp;\<br />
(2)&nbsp;(7)<br />
/&nbsp;\&nbsp;\<br />
(3)&nbsp;(4)&nbsp;(8)<br />
/&nbsp;\<br />
(5)&nbsp;(6)<br />
<br />
一个nlogn&nbsp;预处理，O(1)查询的算法.<br />
Step&nbsp;1:<br />
按先序遍历整棵树，记下两个信息:结点访问顺序和结点深度.<br />
如上图:<br />
结点访问顺序是:&nbsp;1&nbsp;2&nbsp;3&nbsp;2&nbsp;4&nbsp;5&nbsp;4&nbsp;6&nbsp;4&nbsp;2&nbsp;1&nbsp;7&nbsp;8&nbsp;7&nbsp;1&nbsp;//共2n-1个值<br />
结点对应深度是:&nbsp;0&nbsp;1&nbsp;2&nbsp;1&nbsp;2&nbsp;3&nbsp;2&nbsp;3&nbsp;2&nbsp;1&nbsp;0&nbsp;1&nbsp;2&nbsp;1&nbsp;0<br />
Step&nbsp;2:<br />
如果查询结点3与结点6的公共祖先,则考虑在访问顺序中<br />
3第一次出现，到6第一次出现的子序列:&nbsp;3&nbsp;2&nbsp;4&nbsp;5&nbsp;4&nbsp;6.<br />
这显然是由结点3到结点6的一条路径.<br />
在这条路径中，深度最小的就是最近公共祖先(LCA).&nbsp;即<br />
结点2是3和6的LCA.<br />
Step&nbsp;3:<br />
于是问题转化为,&nbsp;给定一个数组R,及两个数字i,j,如何找出<br />
数组R中从i位置到j位置的最小值..<br />
如上例,就是R[]={0,1,2,1,2,3,2,3,2,1,0,1,2,1,0}.<br />
i=2;j=7;<br />
这个问题就是经典的RMQ问题.<br />
这里介绍一个比较简单的方法O(nlogn)预处理，O(1)回答每个询问.<br />
RMQ问题的预处理:<br />
用一个数组d[i][j]表示数组R中，从i位置到i+2^j-1位置的最小值.<br />
这个d[i][j]很容易dp得到.<br />
d[i][j+1]=min{d[i][j],d[i+2^j][j]};<br />
空间:&nbsp;O(nlogn)&nbsp;时间:&nbsp;O(nlogn).<br />
Step&nbsp;4:<br />
询问:<br />
如果询问:从a到b里面最小的值..主要思路找两个长度是2^k的区间:<br />
[a,a+2^k-1]及[b-1-2^k,b]把区间[a,b]覆盖掉.&nbsp;这很容易做到的,<br />
只要:&nbsp;2^k*2&gt;=&nbsp;|b-a|.<br />
于是a到b里面的最小值&nbsp;=&nbsp;min&nbsp;{d[a][k],d[b-2^k-1][k]}<br />
<br />
利用并查集优越的时空复杂度，我们可以实现LCA问题的O(n+Q)算法，这里Q表示询问的次数。<br />
<br />
Tarjan算法基于深度优先搜索的框架，对于新搜索到的一个结点，首先创建由这个结点构成的集合，再对当前结点的每一个子树进行搜索，每搜索完一棵子树，则可确定子树内的LCA询问都已解决。其他的LCA询问的结果必然在这个子树之外，这时把子树所形成的集合与当前结点的集合合并，并将当前结点设为这个集合的祖先。之后继续搜索下一棵子树，直到当前结点的所有子树搜索完。这时把当前结点也设为已被检查过的，同时可以处理有关当前结点的LCA询问，如果有一个从当前结点到结点v的询问，且v已被检查过，则由于进行的是深度优先搜索，当前结点与v的最近公共祖先一定还没有被检查，而这个最近公共祖先的包涵v的子树一定已经搜索过了，那么这个最近公共祖先一定是v所在集合的祖先。<br />
下面给出这个算法的伪代码描述：<br />
以下内容为程序代码:<br />
LCA(u)<br />
{<br />
Make-Set(u)<br />
ancestor[Find-Set(u)]=u<br />
对于u的每一个孩子v<br />
{<br />
LCA(v)<br />
Union(u)<br />
ancestor[Find-Set(u)]=u<br />
}<br />
checked[u]=true<br />
对于每个(u,v)属于P<br />
{<br />
if&nbsp;checked[v]=true<br />
then&nbsp;{<br />
回答u和v的最近公共祖先为&nbsp;ancestor[Find-Set(v)]<br />
}<br />
}<br />
}<br />
<br />
<br />
二、LCA问题向RMQ问题的转化方法<br />
1、LCA问题<br />
对于有根树T的两个结点u、v，最近公共祖先LCA(T,u,v)表示一个结点x，满足x是u、v的祖先且x的深度尽可能大。另一种理解方式是把T理解为一个无向无环图，而LCA(T,u,v)即u到v的最短路上深度最小的点。<br />
这里给出一个LCA的例子：<br />
例一<br />
对于T=<v,e><br />
V={1,2,3,4,5}<br />
E={(1,2),(1,3),(3,4),(3,5)}<br />
则有：<br />
LCA(T,5,2)=1<br />
LCA(T,3,4)=3<br />
LCA(T,4,5)=3<br />
<br />
<br />
2、RMQ问题(Range&nbsp;Minimum&nbsp;Query)<br />
RMQ问题是指：对于长度为n的数列A，回答若干询问RMQ(A,i,j)(i,j&lt;=n)，返回数列A中下标在[i,j]里的最小值下标。这时一个RMQ问题的例子：<br />
例二<br />
对数列：5,8,1,3,6,4,9,5,7&nbsp;有：<br />
RMQ(2,4)=3<br />
RMQ(6,9)=6<br />
RMQ问题与LCA问题的关系紧密，可以相互转换，相应的求解算法也有异曲同工之妙。<br />
下面给出LCA问题向RMQ问题的转化方法。<br />
对树进行深度优先遍历，每当&ldquo;进入&rdquo;或回溯到某个结点时，将这个结点的深度存入数组E最后一位。同时记录结点i在数组中第一次出现的位置(事实上就是进入结点i时记录的位置)，记做R[i]。如果结点E[i]的深度记做D[i]，易见，这时求LCA(T,u,v)，就等价于求E[RMQ(D,R[u],R[v])]，(R[u]<r[v])。例如，对于第一节的例一，求解步骤如下： br="">数列E[i]为：1,2,1,3,4,3,5,3,1<br />
R[i]为：1,2,4,5,7<br />
D[i]为：0,1,0,1,2,1,2,1,0<br />
于是有：<br />
LCA(T,5,2)&nbsp;=&nbsp;E[RMQ(D,R[2],R[5])]&nbsp;=&nbsp;E[RMQ(D,2,7)]&nbsp;=&nbsp;E[3]&nbsp;=&nbsp;1<br />
LCA(T,3,4)&nbsp;=&nbsp;E[RMQ(D,R[3],R[4])]&nbsp;=&nbsp;E[RMQ(D,4,5)]&nbsp;=&nbsp;E[4]&nbsp;=&nbsp;3<br />
LCA(T,4,5)&nbsp;=&nbsp;E[RMQ(D,R[4],R[5])]&nbsp;=&nbsp;E[RMQ(D,5,7)]&nbsp;=&nbsp;E[6]&nbsp;=&nbsp;3<br />
易知，转化后得到的数列长度为树的结点数的两倍加一，所以转化后的RMQ问题与LCA问题的规模同次&nbsp;。&nbsp;</r[v])。例如，对于第一节的例一，求解步骤如下：></v,e></v,e></q;i++){></m)+1][m]);></m)+1][m]);></b?a:b)></math.h></iostream></p> 

 
 # 输入格式 
<p>输入&ldquo;yes&rdquo;</p> 

 
 # 输出格式 
<p>输出&quot;no&nbsp;solution&quot;</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td></td><td></td></tr></table>
