<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明面前有n盏灯排成一列。只有若干盏灯是开着的。<strong>每秒钟</strong>小明都会把<strong>所有亮着的灯</strong>的<strong>相邻的两盏灯</strong>的开关按一下。<br>小明经过几百年(t秒钟)后终于结束了这个脑残的游戏，那么这时灯的开关情况如何呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个用空格隔开的整数n和t。<br>第二行，n个用空格隔开的数(0或1)，表示第i盏灯开始时是否亮着。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，n个空格隔开的数，表示第i盏灯是否亮着(0或1)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 10<br>1 0 0 1 1 0 1 0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 0 0 0 0 1 0 0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，m&lt;=50,b&lt;=int；</p>
<p> </p>
<p>样例中初始 <span style="">1 0 0 1 1 0 1 0 1 1</span></p>
<p><span style="">第一秒操作 1 1 1 0 0 0 1 0 0 0 </span></p>
<p><span style="">第二秒操作 0 1 0 1 0 1 1 1 0 0  </span></p>
<p><span style="">第三秒操作 1 1 0 1 0 0 1 0 1 0 </span></p>
<p><span style="">第四秒操作 0 0 0 1 1 1 1 0 1 1 </span></p>
<p><span style="">…………</span></p>
<p><span style="">又如 1 0 1 的下一秒情况是 1 0 1 </span></p>
<p><span style="">【因为中间那盏灯分别和第一第三盏灯相邻，会被同时按两次】</span></p>
</div>
</div>