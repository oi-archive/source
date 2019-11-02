<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>奶牛们开始对用射电望远镜扫描牧场外的宇宙感兴趣。最近，他们注意到了一种非常奇怪的脉冲调制微波从星系的中央发射出来。他们希望知道电波是否是被某些地外生命发射出来的，还是仅仅是普通的的星星发出的。</p>
<p>帮助奶牛们用一个能够分析他们在文件中记下的记录的工具来找到真相。他们在寻找长度在A到B之间（包含A和B本身）在每天的数据文件中重复得最多的比特序列 (1 &lt;= A &lt;= B &lt;= 12)。他们在找那些重复得最多的比特序列。一个输入限制告诉你应输出多少频率最多的序列。</p>
<p>符合的序列可能会重叠，并且至少出现一次的序列会被计数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行： 三个用空格分隔的整数: A, B, N; (1 &lt;= N &lt; 50)</p>
<p>第二行及以后: 一个最多200，000字符的序列，全是0或1; 每行字符数不大于80。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出N个频率最高的序列（按照频率由高到低的次序）。由短到长排列频率相同的这些序列，如果长短相同，按二进制大小排列。如果出现的序列个数小于N，输出存在的序列。</p>
<p>对于每个存在的频率，先输出单独包含该频率的一行，再输出以空格分隔的这些序列。每行六个（除非少于六个剩下）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>2 4 10
01010010010001000111101100001010011001111000010010011110010000000</pre>
<pre><span>在样例里，序列100出现了12次，而序列1000出现了5次。次数最多的序列是00，出现了23次。</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>23
00
15
01 10
12
100
11
11 000 001
10
010
8
0100
7
0010 1001
6
111 0000
5
011 110 1000
4
0001 0011 1100</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>上</p>
</div>
</div>