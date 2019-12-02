# 

 
 # 题目描述 
<p><span style="line-height: 20.8px;">给你一个完全图，有n个节点，标号为1..n</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">每个点的权值就是自己的标号</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">查询图中最小生成树有多少个，这个的最小生成树必须满足父亲节点的标号小于自己,边的权值是连接的两个点的标号的gcd</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">有3个操作</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">D&nbsp;u&nbsp;v&nbsp;删除边(u,v)，保证有边相连。&nbsp;</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">Q&nbsp;查询最小生成树有多少个</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">S&nbsp;查询当前的最小生成树权值和为多少</span><br style="line-height: 20.8px;" />
<span style="line-height: 20.8px;">A&nbsp;加一个节点，标号为当前最大的节点的标号+1，并且将他和每个节点连接一条边</span><span style="line-height: 20.8px;">格式</span></p> 

 
 # 输入格式 
<p><br />
输入：<br />
第一行两个数n,m<br />
然后m行表示操作数</p> 

 
 # 输出格式 
<p>输出答案</p> 

 
 # 提示 
<p>数据范围：<br />
10%&nbsp;n&lt;=10&nbsp;m&lt;=10&nbsp;并且只有查询操作<br />
20%&nbsp;n&lt;=1000&nbsp;m&lt;=1000&nbsp;并且只有查询操作和加点操作<br />
60%&nbsp;n&lt;=30000&nbsp;m&lt;=30000&nbsp;保证图的连通性，并且每个节点被删除的边的个数不会超过200个,Q操作不超过20次<br />
答案&nbsp;mod&nbsp;10000007</p> 
