<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们用N(1 &lt;= N &lt;=5000)个音符的序列来表示一首乐曲，每个音符都是1..88范围内的整数，每个数表示钢琴上的一个键。很不幸这种表示旋律的方法忽略了音符的时值，但这项编程任务是关于音高的，与时值无关。</p>
<p>许多作曲家围绕一个重复出现的“主题”来构建乐曲。在我们的乐曲表示法中，“主题”是整个音符序列的一个子串，它需要满足如下条件：</p>
<p>⒈长度至少为5个音符</p>
<p>⒉在乐曲中重复出现(可能经过转调，见下)</p>
<p>⒊重复出现的同一主题不能有公共部分。</p>
<p>“转调”的意思是主题序列中每个音符都被加上或减去了同一个整数值。 给定一段乐曲，计算其中最长主题的长度(即音符数)。</p>
<p>本题时限为1秒钟!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件的第一行包含整数N。下面的每一行(最后一行可能除外)包含20个整数，表示音符序列。最后一行可能少于20个音符。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出文件应只含一个整数，即最长主题的长度。如果乐曲中没有主题，那么输出0。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>30
25 27 30 34 39 45 52 60 69 79 69 60 52 45 39 34 30 26 22 18
82 78 74 70 66 67 64 60 65 80</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>