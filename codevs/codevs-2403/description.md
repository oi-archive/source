<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>a180285幸运地被选做了地球到喵星球的留学生。他发现喵星人在上课前的点名现象非常有趣。 <br> 假设课堂上有 N 个喵星人，每个喵星人的名字由姓和名构成。喵星球上的老师会选择M 个串来点名，每次读出一个串的时候，如果这个串是一个喵星人的姓或名的子串，那么这个喵星人就必须答到。 <br>然而，由于喵星人的字码过于古怪，以至于不能用 ASCII 码来表示。为了方便描述，a180285决定用数串来表示喵星人的名字。 <br>现在你能帮助 a180285 统计每次点名的时候有多少喵星人答到，以及 M 次点名结束后每个喵星人答到多少次吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>现在定义喵星球上的字符串给定方法： <br> 先给出一个正整数 L，表示字符串的长度，接下来L个整数表示字符串的每个字符。 <br> 输入的第一行是两个整数N和M。 <br> 接下来有N行，每行包含第 i个喵星人的姓和名两个串。姓和名都是标准的喵星球上的字符串。 <br> 接下来有M行，每行包含一个喵星球上的字符串，表示老师点名的串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个老师点名的串输出有多少个喵星人应该答到。 <br />然后在最后一行输出每个喵星人被点到多少次。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3 <br>6 8 25 0 24 14 8 6 18 0 10 20 24 0 <br>7 14 17 8 7 0 17 0 5 8 25 0 24 0 <br>4 8 25 0 24 <br>4 7 0 17 0 <br>4 17 0 8 25</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br>1 <br>0 <br>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证： <br>1 &lt;= M, N &lt;= 1000<br> 喵星人的名字总长不超过 4000，点名串的总长不超过 2000， <br>对于100%的数据，保证： <br>1&lt;=N&lt;=20000<br>1&lt;=M&lt;=50000<br>喵星人的名字总长和点名串的总长分别不超过<br>100000 保证喵星人的字符串中作为字符存在的数不超过 10000</p>
</div>
</div>