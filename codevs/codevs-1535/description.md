<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>曹是一只爱刷街的老曹，暑假期间，他每天都欢快地在阳光大学的校园里刷街。河蟹看到欢快的曹，感到不爽。河蟹决定封锁阳光大学，不让曹刷街。</p>
<p>阳光大学的校园是一张由N个点构成的无向图，N个点之间由M条道路连接。每只河蟹可以对一个点进行封锁，当某个点被封锁后，与这个点相连的道路就被封锁了，曹就无法在与这些道路上刷街了。非常悲剧的一点是，河蟹是一种不和谐的生物，当两只河蟹封锁了相邻的两个点时，他们会发生冲突。</p>
<p>询问：最少需要多少只河蟹，可以封锁所有道路并且不发生冲突。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个整数N，M</p>
<p>接下来M行：每行两个整数A，B，表示点A到点B之间有道路相连。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅一行：如果河蟹无法封锁所有道路，则输出&ldquo;Impossible&rdquo;，否则输出一个整数，表示最少需要多少只河蟹。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】</p>
<p>3 3</p>
<p>1 2</p>
<p>1 3</p>
<p>2 3</p>
<p>【输入样例2】</p>
<p>3 2</p>
<p>1 2</p>
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】</p>
<p>Impossible</p>
<p>【输出样例2】</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】</p>
<p>1&lt;=N&lt;=10000，1&lt;=M&lt;=100000，任意两点之间最多有一条道路。</p>
</div>
</div>