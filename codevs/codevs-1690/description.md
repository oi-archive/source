<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    YYX家门前的街上有N(2&lt;=N&lt;=100000)盏路灯，在晚上六点之前，这些路灯全是关着的，六点之后，会有M(2&lt;=m&lt;=100000)个人陆续按下开关，这些开关可以改变从第i盏灯到第j盏灯的状态，现在YYX想知道，从第x盏灯到第y盏灯中有多少是亮着的(1&lt;=i,j,x,y&lt;=N)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>第 1 行: 用空格隔开的两个整数N和M</div>
<div>第 2..M+1 行: 每行表示一个操作, 有三个用空格分开的整数: 指令号(0代表按下开关，1代表询问状态), x 和 y </div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第 1..询问总次数 行:对于每一次询问，输出询问的结果</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 5<br>0 1 2<br>0 2 4<br>1 2 3<br>0 2 4<br>1 1 4<br><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div><span>1<br>2</span></div>
<div><span><br></span></div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>一共4盏灯，5个操作，下面是每次操作的状态(X代表关上的，O代表开着的)：</p>
<p>XXXX -&gt; OOXX -&gt; OXOO -&gt; 询问1~3 -&gt; OOXX -&gt; 询问1~4</p>
</div>
</div>