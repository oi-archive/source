<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一棵结点数为n的树，初始点权均为0，有依次q个操作，每次操作有三个参数a,b,c，当a=1时，表示给b号结点到c号结点路径上的所有点（包括b,c，下同）权值都增加1，当a=2时，表示询问b号结点到c号结点路径上的所有点权值之和。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个正整数n。</p><p>接下来n-1行，每行一对正整数x,y，表示x号结点和y号结点之间有一条边。</p><p>第n+1行，一个正整数q。</p><p>最后q行，每行一组正整数a,b,c，表示操作的三个参数。b和c可能相等。</p><p>保证数据都是合法的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干行，每行一个非负整数表示答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>1 2</p><p>2 3</p><p>1 4</p><p>2 5</p><p>5</p><p>1 4 5</p><p>2 1 5</p><p>1 1 3</p><p>2 5 3</p><p>2 4 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>4</p><p>6</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>共有10个测试点，对于第i个测试点，当1&lt;=i&lt;=4时，n=q=10^i，当5&lt;=i&lt;=10时，n=q=10000*i。</p>
</div>
</div>