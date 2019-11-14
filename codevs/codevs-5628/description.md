<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>徐来“大神”写了一个程序，并在众oier面前炫耀：</p><p><br></p><p>“我这个程序可以处理数据，是前无古人后无来者的程序。它有好多操作：</p><p>1、 查询操作。语法：Q L 功能：查询当前数列中末尾L个数中的最大的数，并输出这个数的值。限制：L不超过当前数列的长度。</p><p>2、 插入操作。语法：A n 功能：将n加上t，其中t是最近一次查询操作的答案（如果还未执行过查询操作，则t=0)，并将所得结果对一个固定的常数D取模，将所得答案插入到数列的?末尾。限制：n是非负整数并且在长整范围内。”</p><p><br></p><p>叶可禾:“谁都会写这种无聊的程序。”</p><p>但他还真不会了，众oier也不肯帮他，于是他只好求助与你，让你帮他写出这个程序。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行两个整数，M和D，其中M表示操作的个数(M &lt;= 200,000)，D如上文中所述，满足D在longint内。接下来M行，查询操作或者插入操作。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="white-space: normal;"><span style="font-family: 微软雅黑, sans-serif;">对于每一个询问操作，输出一行。该行只有一个数，即序列中最后L个数的最大数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 100</span></p><p><span style="">A 96</span></p><p><span style="">Q 1</span></p><p><span style="">A 97</span></p><p><span style="">Q 1</span></p><p><span style="">Q 2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">96</span></p><p><span style="">93</span></p><p><span style="">96</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">M &lt;= 200,000</span></p><p>注意：初始时数列是空的，没有一个数。</p>
</div>
</div>