<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>检查一个如下的6 x 6的跳棋棋盘，有六个棋子被放置在棋盘上，使得每行、每列只有一个，每条对角线(包括两条主对角线的所有平行线)上至多有一个棋子。</p>
<p>列号<br>　 1　 2　 3　 4　 5　 6</p>
<p>　-------------------------</p>
<p>1 |　 | O |　 |　 |　 |　 |</p>
<p>　-------------------------</p>
<p>2 |　 |　 |　 | O |　 |　 |</p>
<p>　-------------------------</p>
<p>3 |　 |　 |　 |　 |　 | O |</p>
<p>　-------------------------</p>
<p>4 | O |　 |　 |　 |　 |　 |</p>
<p>　-------------------------</p>
<p>5 |　 |　 | O |　 |　 |　 |</p>
<p>　-------------------------</p>
<p>6 |　 |　 |　 |　 | O |　 |</p>
<p>　-------------------------</p>
<p>上面的布局可以用序列2 4 6 1 3 5来描述，第i个数字表示在第i行的相应位置有一个棋子，如下： <br>行号 1 2 3 4 5 6 <br>列号 2 4 6 1 3 5 <br>这只是跳棋放置的一个解。请编一个程序找出所有跳棋放置的解。并把它们以上面的序列方法输出。解按字典顺序排列。请输出前3个解。最后一行是解的总个数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个数字N表示棋盘是N x N大小的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>前三行为前三个解，每个解的两个数字之间用一个空格隔开。第四行只有一个数字，表示解的总数。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 4 6 1 3 5 <br>3 6 2 5 1 4 <br>4 1 5 2 6 3 <br>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>6 &lt;= N &lt;= 13</p>
</div>
</div>