<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这一天，PLQ和他的小伙伴们在大街上走着，突然他们看见了一件令人惊讶的事情，他们决定要惊呆。初始情况下他们的惊呆指数均为0。</p>
<p>已知PLQ和他的小伙伴们一共有n名，编好从1到n，顺时针排成一个环，如图所示。</p>
&lt;h4&gt;<img style="">&lt;/h4&gt;
<p> </p>
<p>他们决定以报数的形式来惊呆，一开始让编号为a的人开始报数，他报1，之后顺时针报下去。报到X1的人惊呆指数加1；然后下一个人再从1开始报数，报到X2的人惊呆指数加1,；如此m轮之后，每个人的惊呆指数都能确定。回来之后，他准备来考考你这个神犇，他只告诉你X1~Xm和每个人的最终惊呆指数，要你快速求出a来。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入有3行，第一行有两个用空格隔开的正整数n和m，第二行有m个用空格隔开的正整数，第i个为Xi，第三行有n个用空格隔开的正整数，第j个为Yj，表示编号为j的人的最终惊呆指数为Yj。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出有一行或两行，若能算出唯一的a则只输出一行，这一行只有一个正整数a。如果不能确定（即有多个可能），请输出&ldquo;Cannot determine!&rdquo;（不含引号），并在第二行输出可能的方案数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre><span style="">【样例输入1】</span></pre>
<pre><span style="">5 6</span></pre>
<pre><span style="">2 2 3 4 5 1</span></pre>
<pre><span style="">0 2 3 0 1</span></pre>
<pre><span style="">【样例输入2】</span></pre>
<pre>4 6</pre>
<pre>1 3 2 1 3 2</pre>
<pre>2 1 2 1
</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br>2<br>【样例输出2】<br>Cannot determine!<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据，0&lt;n≤1000000，0&lt;m≤2000000，0&lt;Xi≤1000000000，0≤Yj≤m。</p>
<p> </p>
<p>题目来源于CH上的Beta Round #9 Problem C，原作者为lll6924。</p>
</div>
</div>