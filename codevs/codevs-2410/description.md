<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个合法的括号序列是这样定义的：</p>
<ol>
<li>空串是合法的。</li>
<li>如果字符串S是合法的，则(S)也是合法的。</li>
<li> 3. 如果字符串A和B是合法的，则AB也是合法的。</li>
</ol>
<p>现在给你一个长度为N的由‘('和‘)'组成的字符串，位置标号从1到N。对这个字符串</p>
<p>有下列四种操作：</p>
<ol>
<li>Replace a b c：将[a,b]之间的所有括号改成c。例如：假设原来的字符串为：))())())(，那么执行操作Replace 2 7 ( 后原来的字符串变为：)(((((()(。</li>
<li>Swap a b：将[a,b]之间的字符串翻转。例如：假设原来的字符串为：))())())(，那么执行操作Swap 3 5后原来的字符串变为：))))(())(。</li>
<li>Invert a b：将[a,b]之间的‘(’变成‘)’,‘)’变成‘(’。例如：假设原来的字符串为：))())())(，那么执行操作Invert 4 8后原来的字符串变为：))((()(((。</li>
<li>Query a b：询问[a,b]之间的字符串至少要改变多少位才能变成合法的括号序列。改变某位是指将该位的‘(’变成‘)’或‘)’变成‘(’。注意执行操作 Query 并不改变当前的括号序列。例如：假设原来的字符串为：))())())(，那么执行操作Query 3 6的结果为2，因为要将位置5的‘)’变成‘(’并将位置6的‘(’变成‘)’。 </li>
</ol>

<img src="/source/codevs/codevs-2410/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzI0MTAuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是用空格隔开的两个正整数N和M，分别表示字符串的长度和将执行的操作个数。第二行是长度为N的初始字符串S。接下来的M行是将依次执行的M个操作，其中操作名与操作数之间以及相邻操作数之间均用空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含T行，其中T是输入的将执行的M个操作中Query操作出现的次数。Query 操作的每次出现依次对应输出文件中的一行，该行只有一个非负整数，表示执行对应Query操作的结果，即：所指字符串至少要改变多少位才能变成合法的括号序列。输入数据<span>保证问题有解。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5<br>((((<br>Replace 1 2 )<br>Query 1 2<br>Swap 2 3<br>Invert 3 4<br>Query 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 样例解释见图片</p>
<p>30%的数据满足N,M≤3000。100%的数据满足N,M≤100000。 </p>
</div>
</div>