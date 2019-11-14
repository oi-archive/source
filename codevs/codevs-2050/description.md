<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在IOI98的节日宴会上，我们有N(10&lt;=N&lt;=100)盏彩色灯，他们分别从1到N被标上号码。 这些灯都连接到四个按钮：</p>
<pre>按钮1：当按下此按钮，将改变所有的灯：本来亮着的灯就熄灭，本来是关着的灯被点亮。
按钮2：当按下此按钮，将改变所有奇数号的灯。
按钮3：当按下此按钮，将改变所有偶数号的灯。
按钮4：当按下此按钮，将改变所有序号是3*K+1(K&gt;=0)的灯。例如：1,4,7...
</pre>
<p>一个计数器C记录按钮被按下的次数。当宴会开始，所有的灯都亮着，此时计数器C为0。</p>
<p>你将得到计数器C(0&lt;=C&lt;=10000)上的数值和经过若干操作后某些灯的状态。写一个程序去找出所有灯最后可能的与所给出信息相符的状态，并且没有重复。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>不会有灯会在输入中出现两次。</p>
<p>第一行: N。</p>
<p>第二行: C最后显示的数值。</p>
<p>第三行: 最后亮着的灯,用一个空格分开，以-1为结束。</p>
<p>第四行: 最后关着的灯,用一个空格分开，以-1为结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每一行是所有灯可能的最后状态(没有重复)。每一行有N个字符，第1个字符表示1号灯，最后一个字符表示N号灯。0表示关闭，1表示亮着。这些行必须从小到大排列（看作是二进制数）。</p>
<p>如果没有可能的状态，则输出一行'IMPOSSIBLE'。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>10
1
-1
7 -1
</pre>
<p>在这个样例中，有10盏灯，只有1个按钮被按下。最后7号灯是关着的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>0000000000
0101010101
0110110110
</pre>
<p>在这个样例中，有三种可能的状态：</p>
<p>所有灯都关着</p>
<p>1,4,7,10号灯关着，2,3,5,6,8,9亮着。</p>
<p>1,3,5,7,9号灯关着，2, 4, 6, 8, 10亮着。</p>

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