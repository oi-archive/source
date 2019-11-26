<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       城市C是一个非常繁忙的大都市，城市中的道路十分的拥挤，于是市长决定对其中的道路进行改造。城市C的道路是这样分布的：城市中有n个交叉路口，有些交叉路口之间有道路相连，两个交叉路口之间最多有一条道路相连接。这些道路是双向的，<strong>且把所有的交叉路口直接或间接的连接起来了</strong>。每条道路都有一个分值，分值越小表示这个道路越繁忙，越需要进行改造。但是市政府的资金有限，市长希望进行改造的道路越少越好，于是他提出下面的要求：</p>
<p>1．  改造的那些道路能够把所有的交叉路口直接或间接的连通起来。</p>
<p>2．  在满足要求1的情况下，改造的道路尽量少。</p>
<p>3．  在满足要求1、2的情况下，改造的那些道路中分值最大的道路分值尽量小。</p>
<p><strong>任务：</strong>作为市规划局的你，应当作出最佳的决策，选择那些道路应当被修建。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数n,m表示城市有n个交叉路口，m条道路。接下来m行是对每条道路的描述，u, v, c表示交叉路口u和v之间有道路相连，分值为c。(1≤n≤300，1≤c≤10000)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个整数s, max，表示你选出了几条道路，分值最大的那条道路的分值是多少。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>4 5</pre>
<pre>1 2 3</pre>
<pre>1 4 5</pre>
<p>  2 4 7</p>
<pre><span>2 3 6</span></pre>
<pre><span>3 4 8</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre><span>3 6</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>