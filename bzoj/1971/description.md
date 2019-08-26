
# Description

<div class="content">Byteotian 基础服务政府准备研发一个计算机程序来帮助他们快速的找出两个城镇之间不同的路径.如果居民总是想找出最短的路径的话还是不难的.但是不幸的是,他们有时候想知道第k短的路径.而且除此之外,路径中自环,重复经过点是允许的. 
如果两个城镇之间有4条路径,他们的长度分别是2, 4, 4 and 5, 那么最短路径的长度为2,次长为4,第三长为4,第四长的长度为5. 
</div>

# Input

<div class="content">In the first line of the standard input there are two positive integers n and m, separated by a single space, 1 &lt;= n &lt;= 100, 0 &lt;= m &lt;= n^2-n. They are the number of towns in Byteotia and the number of roads connecting the towns, respectively. The towns are numbered from 1 to n.

In each of m successive lines there are three integers separated by single spaces: a, b and l, a &lt;&gt; b, 1 &lt;= l &lt;= 500. Each triple describes one one-way road of length l enabling to move from the town a to b. For each two towns there exist at most one road that enables to move in the given direction.

In the following line there is one integer q, 1 &lt;= q &lt;= 10000, denoting the number of queries. In the successive q lines there are queries written, one per line. Each query has a form of three integers separated by single spaces: c, d and k, 1 &lt;= k &lt;= 100. Such a query refers to the length of the k-th shortest route from the town c to the town d.




输入文件的第一行有两个数n and m, 1 &lt;= n &lt;= 100, 0 &lt;= m &lt;= n^2-n. 他们分别代表城镇总数和连接他们的道路总数. 城镇编号从1 到 n.
接下来m 行每行3个整数: a, b 和 l, a &lt;&gt; b, 1 &lt;= l &lt;= 500. 他们代表一条长度为l有向边从a 到 b. 不会有两条边有着相同的起点和终点.
接下来一行是一个整数q, 1 &lt;= q &lt;= 10000, 代表一共有q个询问. 接下来q 行每行三个数: c, d 和 k, 1 &lt;= k &lt;= 100. 表示询问城镇c 到城镇d的第k短路.
</div>

# Output

<div class="content">对于每个询问,输出一行表示询问路径的长度,如果答案不存在,输出-1. 
</div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 3<br/>
2 3 2<br/>
3 2 1<br/>
1 3 10<br/>
1 4 1<br/>
8<br/>
1 3 1<br/>
1 3 2<br/>
1 3 3<br/>
1 4 2<br/>
2 5 1<br/>
2 2 1<br/>
2 2 2<br/>
1 1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
8<br/>
10<br/>
-1<br/>
-1<br/>
3<br/>
6<br/>
-1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

