# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
积木游戏是一种创造建筑物的游戏，像所有的玩具积木游戏一样，它也是使用一组积木来搭建建筑物。
</p>
<p>
在这个问题中，考虑一个用一组积木搭建的长方形建筑，我们的任务是从建筑中移走K块积木，使得剩余的积木保持稳定，剩余的积木需满足下面要求：
</p>
<p>
（1）剩余建筑中的每一层都由一些在行中连续的积木所组成；
</p>
<p>
（2）每一层都至少要有一块积木有下层积木的支撑；
</p>
<p>
（3）在最底层要保留至少一块积木。
</p>
<p>
每块积木都有一个目测值（为一个非负整数刻在其表面上），我们希望剩余积木的目测值总和最大，你能告诉我们这个和是多少吗？
</p>
<p>
举例说明，下面为输入样例所对应的图示，右边为按照上述规则所得到的最优解，请注意，因为没有规定有多少层必须保留，所以我们可以丢弃最上面的一些层。
</p>
<p>
<img src="/upload/image/20140425/20140425055549_39764.jpg" alt=""/> 
</p>
<p>
<br/>
</p>
<p>
 原始建筑                                                         最优解
</p>
<p>
<br/>
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
输入文件第一行有一个正整数T(T&lt;=20)，表示接下来测试数据的个数。
</p>
<p>
每个测试数据的第一行有三个整数：N，M，K，(0&lt;N,M&lt;=64;max(NM-64,0)&lt;=K&lt;NM)。
</p>
<p>
接下来有N行，每行有M个整数，为每个积木的目测值，第一行表示建筑的最上层，最后一行为建筑的最底层。所有的目测值均为小于32768的非负整数。
</p>
<p>
所有数都由空格隔开。
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
对于每个测试数据，输出只有一行，形如“Case X:Y”(不包括双引号)，其中X表示测试数据的编号（从1开始），Y表示最大总和。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>1
6 4 12
1 1 1 1
1 7 14 1
9 4 18 18 
2 4 5 5
1 7 1 11
3 2 7 16
</pre>
<h3>
【样例输出】
</h3>
<pre>Case 1:118</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>