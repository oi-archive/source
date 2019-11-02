<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>等差数列的定义是一个数列S，它满足了(S[i]-S[i-1]) = d (i&gt;1)。显然的一个单独的数字或者两个数字也可以形成一个等差数列。<br>经过一定的学习小C发现这个问题太简单了，等差数列的和不就是(Sn+S1)*n/2？因为这个问题实在是太简单了，小C不屑于去解决它。这让小C的老师愤怒了，他就找了另外一个问题来问他。<br>小C的老师给了他一个长度为N的数字序列，每个位置有一个整数，他需要小C帮他找到这个数字序列里面有多少个等差数列。<br>……<br>这个问题似乎太难了，小C需要你的程序帮他来解决这个问题。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N，表示老师给出的数字序列的长度。<br>第二行有N个整数A[i]，表示数字序列每个数字的大小。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行一个整数，表示这个序列中的等差数列的个数（mod 9901）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>1 4 2 3 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，N &lt;= 100<br>对于70%的数据，N &lt;= 500<br>对于100%的数据，N &lt;= 1000；-500 &lt;= A[i] &lt;= 500</p>
<p> </p>
</div>
</div>