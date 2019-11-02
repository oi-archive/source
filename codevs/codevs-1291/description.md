<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某列火车行使在C个城市之间(出发的城市编号为1，结束达到的城市的编号为C)，假设该列火车有S个座位，现在有R笔预订票的业务。现在想对这R笔业务进行处理，看哪些预定能满足，哪些不能满足。</p>
<p>一笔预定由O、D、N三个整数组成，表示从起点站O到目标站D需要预定N个座位。一笔预定能满足是指该笔业务在行程范围内有能满足的空座位，否则就不能满足。一笔业务不能拆分，也就是起点和终点站不能更改，预定的座位数目也不能更改。所有的预定需求按给出先后顺序进行处理。</p>
<p>请你编写程序，看那些预定业务能满足，那些不能满足。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件<tt>中的第一行为三个整数</tt><tt>C</tt><tt>、</tt><tt>S</tt><tt>、</tt><tt>R</tt><tt>，</tt>(1&lt;=<em>c</em>&lt;=60 000, 1&lt;=<em>s</em>&lt;=60 000, 1&lt;=<em>r</em>&lt;=60 000)<tt>他们之间用空隔分开。接下来的</tt><tt>R</tt><tt>行每行为三个整数</tt>O、D、N，(1&lt;=<em>o</em>&lt;<em>d</em>&lt;=<em>c</em>, 1&lt;=<em>n</em>&lt;=<em>s</em>)，分别表示每一笔预定业务。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;对第I笔业务，如果能满足，则在输出文件<tt>中</tt>的第I行输出&ldquo;T&rdquo;，否则输出&ldquo;N&rdquo;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>4 6 4</pre>
<pre>1 4 2</pre>
<pre>1 3 2</pre>
<pre>2 4 3</pre>
<p>1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>T</pre>
<pre>T</pre>
<pre>N</pre>
<p>N</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>