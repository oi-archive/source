# 题目描述


<p>
usaco/Stamps(译by Felicia Crazy)
</p>
<p>
描述
</p>
<p>
<br/>
</p>
<div>
<p>
已知一个N枚邮票的面值集合（如，{1分，3分}）和一个上限K ——表示信封上能够贴K张邮票。计算从1到M的最大连续可贴出的邮资。
</p>
<p>
例如，假设有1分和3分的邮票；你最多可以贴5张邮票。很容易贴出1到5分的邮资（用1分邮票贴就行了），接下来的邮资也不难：
</p>
<ul>
<li>
6 = 3 + 3
</li>
<li>
7 = 3 + 3 + 1
</li>
<li>
8 = 3 + 3 + 1 + 1
</li>
<li>
9 = 3 + 3 + 3
</li>
<li>
10 = 3 + 3 + 3 + 1
</li>
<li>
11 = 3 + 3 + 3 + 1 + 1
</li>
<li>
12 = 3 + 3 + 3 + 3
</li>
<li>
13 = 3 + 3 + 3 + 3 + 1。
</li>
</ul>
<p>
然而，使用5枚1分或者3分的邮票根本不可能贴出14分的邮资。因此，对于这两种邮票的集合和上限K=5，答案是M=13。
</p>
</div>
<div>
</div>
<div>
</div>
<div>
格式
</div>
<div>
PROGRAM NAME: stamps
</div>
<div>
INPUT FORMAT:(file stamps.in)
</div>
<div>
</div>
<div>
<table border="1">
<tbody>
<tr>
<td>
第1行：
</td>
<td>
两个整数，K和N。K（1 &lt;= K &lt;= 200）是可用的邮票总数。N（1 &lt;= N &lt;= 50）是邮票面值的数量。
</td>
</tr>
<tr>
<td>
第2行..文件末：
</td>
<td>
N个整数，每行15个，列出所有的N个邮票的面值，面值不超过10000。
</td>
</tr>
</tbody>
</table>
 
</div>
<div>
OUTPUT FORMAT:(file stamps.out)
</div>
<div>
<p>
单独的一行，一个整数，从 1 分开始连续的可用集合中不多于 K 张邮票贴出的邮资数。
</p>
</div>
<div>
SAMPLE INPUT
<div>
(file stamps.in)
</div>
</div>
<p>
5 2
</p>
<p>
1 3 
</p>
<div>
SAMPLE OUTPUT
<div>
(file stamps.out)
</div>
</div>
<div>
<p>
13 
</p>
</div>
<p>
<br/>
</p>
