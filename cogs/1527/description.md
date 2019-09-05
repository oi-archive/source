# 题目描述


<h3>
【题目描述】
</h3>
<p>
<img src="/upload/image/20140217/20140217200849_15453.jpg" alt=""/> 
</p>
<p>
今天是Tilliby的九岁生日。他收到了各种各样的礼物，例如夜光贴纸，电子计算器，一个新牙刷等等。但是，这个看上去很有趣的多米诺瓷砖拼图吸引了他的注意力。拼图的规则如下所述：拼图由一个R*C的网格组成，并且它必须完全被2*1的瓷砖填充，瓷砖的数量充足。瓷砖不可以重叠。为了使事情复杂化，网格中一些特定的格子被标记为不可使用，它们不能被瓷砖覆盖。不过，除此之外的所有格子都必须恰好被一块瓷砖覆盖。现在，尽管有不可用的格子，这对Tilliby来说就是一个简单的练习。但是，如果要计算出覆盖的方案总数，即使他闪亮的新计算器也帮不了他了。你能帮助他吗？
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含至多100组数据。
</p>
<p>
每组数据的第一行有3个正整数R,C,N。
</p>
<p>
接下来有N行，每行有两个整数ri,ci。其中ri是第i个不可用格子的行数，ci是它的列数。其中，1&lt;=R&lt;=4，1&lt;=C&lt;=100000000，0&lt;=N&lt;=100，0&lt;=ri&lt;R，0&lt;=ci&lt;C。
</p>
<p>
输入结束标志为R=C=N=0，这组数据不用处理。
</p>
<h3>
【输出格式】
</h3>
<p>
每组数据输出一行，格式为&#34;Case c: x&#34;，其中c是数据编号（从1开始），x是填充方案总数。由于x有可能很大，因此只需输出x模10000007的值。
</p>
<h3>
【样例输入】
</h3>
<p>
2 2 0
</p>
<p>
2 4 0
</p>
<p>
2 4 2
</p>
<p>
0 0
</p>
<p>
0 3
</p>
<p>
0 0 0
</p>
<h3>
【样例输出】
</h3>
<p>
Case 1: 2
</p>
<p>
Case 2: 5
</p>
<p>
Case 3: 1
</p>
<h3>
【提示】
</h3>
<p>
对于30%的数据，1&lt;=C&lt;=10.
</p>
<p>
对于50%的数据,1&lt;=C&lt;=1000.
</p>
<p>
对于100%的数据，范围如题中所示。
</p>
<h3>
【来源】
</h3>
<p>
<span style="font-family:serif;background-color:white;font-size:16px;font-weight:normal;line-height:20px;">Problem setter: Samee Zahur Special Thanks: Md. Arifuzzaman Arif</span> 
</p>
<p>
<span style="font-family:serif;background-color:white;font-size:16px;font-weight:normal;line-height:20px;"><a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=572&amp;page=show_problem&amp;problem=2841" target="_blank">UVa11741 Ignore the Blocks</a></span> 
</p>
