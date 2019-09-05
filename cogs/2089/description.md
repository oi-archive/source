# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
树链剖分可以干什么？
</p>
<p>
“可以支持在树中快速修改一个点信息，快速询问一条链信息”
</p>
<p>
LCT可以干什么？
</p>
<p>
“可以支持树链剖分支持的特性，并且支持快速链接两个棵树，或者断开某条边”
</p>
<p>
那我现在要出一道关于树的题目，一开始有n个点，每个点自成一颗树，所以现在有n棵树。每个点有一个权值。有以下这些操作类型：
</p>
<p>
连接操作：1 a b，连接a和b，使a成为b的儿子结点，a一定是某个树的根节点。这样就把两个数连接到一起，此时a以及所有后代的根节点均为b所在树的根节点。
</p>
<p>
询问操作：2 a，询问a到自己所在树的根节点所有在路径（包括自己和根节点）上的所有点的权值的异或和。
</p>
<p>
恩...但是由于我懒，所以还没有造数据，请你帮我写个标程让我用来造数据吧。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行两个整数n和m，表示有n个点和m个操作。
</p>
<p>
接下有一行n个整数，第i个整数表示第i个点的权值。
</p>
<p>
接下来m行，每行为三个整数1 a b，或者2 a。
</p>
<p>
如果是1 a b表示这是一个连接操作，意义见题目。
</p>
<p>
如果是2 a表示这是一个询问操作，意义见题目。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
对于每个询问操作，输出一行，表示从a到根节点路径上所有点的权值的异或和。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5 8
1 2 3 4 5
2 2
1 2 1
2 2
1 4 3
1 3 2
2 3
1 5 1
2 5
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
2
3
0
4
</p>
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
样例解释
</p>
<p>
样例中每个节点权值与标号相同
</p>
<p>
第一个询问中2的根节点是自己，所以第一个询问2节点的答案为0
</p>
<p>
第二个询问中2的根节点是1，路径为2-1，所以答案为2 xor 1 = 3
</p>
<p>
第三个询问中3到根节点的路径为3-2-1，所以答案为3 xor 2 xor 1 = 0
</p>
<p>
第四个询问中5到根节点的路径为5-1，所以答案为5 xor 1 = 4
</p>
<p>
数据范围
</p>
<p>
<br/>
</p>
<p>
对于40%的数据1 &lt;= n,m &lt;= 1000
</p>
<p>
对于90%的数据1 &lt;= n &lt;= 100000, 1 &lt;= m &lt;= 200000
</p>
<p>
对于100%的数据1 &lt;= n &lt;= 300000， 1 &lt;= m &lt;= 500000
</p>
<p>
所有节点的权值均为正整数且在int范围内
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>