<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    Welcome to SAO ( Strange and Abnormal Online)。这是一个VR MMORPG，含有n 个关卡。但是，挑战不同关卡的顺序是一个很大的问题。<br>    有n – 1 个对于挑战关卡的限制，诸如第i 个关卡必须在第j 个关卡前挑战，或者完成了第k 个关卡才能挑战第l 个关卡。并且，如果不考虑限制的方向性，那么在这n – 1 个限制的情况下，任何两个关卡都存在某种程度的关联性。即，我们不能把所有关卡分成两个非空且不相交的子集，使得这两个子集之间没有任何限制。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行，一个整数T，表示数据组数。<br>    对于每组数据，第一行一个整数n，表示关卡数。接下来n – 1 行，每行为“i sign j”，其中0 ≤ i, j ≤ n – 1 且i ≠ j，sign 为“&lt;”或者“&gt;”，表示第i 个关卡必须在第j 个关卡前/后完成。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个数据，输出一行一个整数，为攻克关卡的顺序方案个数，mod1,000,000,007 输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>5<br>0 &lt; 2<br>1 &lt; 2<br>2 &lt; 3<br>2 &lt; 4<br>4<br>0 &lt; 1<br>0 &lt; 2<br>0 &lt; 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4<br> 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据有n ≤ 10。<br>对于40%的数据有n ≤ 100。<br>对于另外20%的数据有，保证数据中sign 只会是&lt;，并且i &lt; j。<br>对于100%的数据有T ≤ 5，1 ≤ n ≤ 1000。</p>
</div>
</div>