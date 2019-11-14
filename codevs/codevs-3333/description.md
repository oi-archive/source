<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>早苗入手了最新的高级打字机。最新款自然有着与以往不同的功能，那就是它具备撤销功能，厉害吧。</p>
<p>请为这种高级打字机设计一个程序，支持如下3种操作：</p>
<p>1.T x：在文章末尾打下一个小写字母x。(type操作)</p>
<p>2.U x：撤销最后的x次修改操作。（Undo操作）</p>
<p>（注意Query操作并不算修改操作）</p>
<p>3.Q x：询问当前文章中第x个字母并输出。（Query操作）</p>
<p>文章一开始可以视为空串。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个整数n，表示操作数量。</p>
<p>以下n行，每行一个命令。保证输入的命令合法。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每行输出一个字母，表示Query操作的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>T a</p>
<p>T b</p>
<p>T c</p>
<p>Q 2</p>
<p>U 2</p>
<p>T c</p>
<p>Q 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>b</p>
<p>c</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%的数据 n&lt;=200;</p>
<p>对于50%的数据 n&lt;=100000；保证Undo操作不会撤销Undo操作。</p>
<p>&lt;高级挑战&gt;</p>
<p>对于100%的数据 n&lt;=100000；Undo操作可以撤销Undo操作。</p>
</div>
</div>