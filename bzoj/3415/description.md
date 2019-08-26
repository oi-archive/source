
# Description

<div class="content"><p><span style="font-size: medium; ">Railway has always been the most popular mean of transport in Byteotia. Out of N towns in the land, M  pairs are connected by track segments belonging to Byteotian State Railways (BSR). The tracks do not cross outside of towns, and may lead through picturesque bridges and somewhat less picturesque tunnels. The ticket for travelling between any two towns directly connected by rail costs a bythalers.<br/>
Currently the transportation market in Byteotia is changing. As of now, BSR faces a new competitor: Byteotian Airlines (BA). BA plans to operate flights between some pairs of towns. Since Byteotian railways are quite comfortable, the BA board has decided to operate flights only between pairs of towns that are not directly connected by rail. Due to economy, BA will fly only between towns for which the cheapest railway connection requires exactly one change. The ticket for each such flight is going to cost b bythalers.<br/>
To help Byteotian citizens in planning their trips, the Byteotian Ministry for Transport (BMT) has decided to issue leaflets specifying the cheapest routes between all possible towns. A sequence of an arbitrary number of direct railway or airplane connections is called a route. A BMT officer by the name of Byteasar has been commissioned with the task of preparing the price list for the leaflets. Could you help him in writing a program that will determine the right prices?<br/>
Let us clarify that all the connections in Byteotia, both by railway and airplane, are bidirectional.<br/>
</span></p>
<p><span style="font-size: medium; ">一个n个点m条边的无向联通图，每条边的权值都是a。</span></p>
<p><span style="font-size: medium; ">定义当前图的i与j最短距离为dis[i][j]。</span></p>
<p><span style="font-size: medium; ">现在改造这个图：对于任何满足dis[u][v]=2a的(u,v)，在u与v之间连一条权值为b的无向边</span></p>
<p><span style="font-size: medium; ">原来的权值为a的边保留</span></p>
<p></p></div>

# Input

<div class="content"><p><font size="4">The first line of the standard input contains five integers n ,m,k,a and b (2&lt;=N&lt;=100000,1&lt;=M&lt;=100000 1&lt;=K&lt;=N 1&lt;=a,b&lt;=1000<br/>
separated by single spaces. The numbers n and m denote the number of towns and the number of direct railway connections in Byteotia, respectively. For simplicity, we number the towns in Byteotia from   to n . The other numbers denote:K  - the number of the source town for which the connection prices are to be determined; a - the price of a direct railway connection;b - the price of a direct airplane connection.<br/>
Each of the following m lines contains a pair of integers Ui and Vi (1&lt;=Ui,Vi&lt;=N Ui&lt;&gt;Vi for i=1,2…..M<br/>
 separated by a single space, specifying the number of towns directly connected by tracks.<br/>
You may assume that all towns are reachable by railway from the town no.k.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should print n lines to the standard output. The line no. I for i=1,2,….N should contain a single integer: the cost of the cheapest route from town no. k to town no. i. Among those, the line no. k should contain the number 0.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 1 3 2<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
3<br/>
3<br/>
2<br/>
5<br/>
<br/>
<br/>
Explanation of the example: The cheapest route from town no. 1 to town no. 5 leads through either town no. 3 or town no. 4. In both cases it consists of a single railway link and a single airplane link.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Wcmg提供译文">鸣谢Wcmg提供译文</a></p></div>

