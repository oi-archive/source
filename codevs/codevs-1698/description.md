<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>小强在N*M的棋盘上摆国际象棋中的“国王”。如果两个“国王”占据的格子有公共边或者公共顶点，那么他们就会相互攻击。现在想知道，一共有多少种不同的方法摆上K个互不攻击的国王呢？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入的第一行包含三个整数，分别表示N、M和K。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出一个整数，表示方法数。如果这个数字超过了2147483647，你只用输出2147483648即可。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>【样例输入1】</span><br><span>3 3 4</span><br><span>【样例输入2】</span><br><span>5 100 50</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>【样例输出1】</span><br><span>1</span><br><span>【样例输出2】</span><br><span>2147483648</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例说明】</span><br><span>第一个样例只有一种可能：</span><br><span>XOX</span><br><span>OOO</span><br><span>XOX</span><br><span>X表示一个国王，O表示一个空格子。</span><br><span>第二个样例的方法数显然多于2147483647。</span><br><span>【数据规模】</span><br><span>对70%的数据，N&lt;=5，M&lt;=5，0&lt;=K&lt;=4</span><br><span>对另外30%的数据，N&lt;=5，M&lt;=100，0&lt;=K&lt;=N*M</span></p>
</div>
</div>