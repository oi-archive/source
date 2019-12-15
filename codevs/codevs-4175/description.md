<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    </span><span style="">在某个遥远的国家里，有n个城市。编号为1，2，3，……，n。</span></p><p><span style="">    </span><span style="">这个国家的政府修建了m条双向的公路。每条公路连接着两个城市。沿着某条公路，开车从一个城市到另一个城市，需要花费一定的汽油。</span></p><p><span style="">    </span><span style="">开车每经过一个城市，都会被收取一定的费用（包括起点和终点城市）。所有的收费站都在城市中，在城市间的公路上没有任何的收费站。</span></p><p><span style="">    </span><span style="">小红现在要开车从城市u到城市v(1&lt;=u，v&lt;=n)。她的车最多可以装下s升的汽油。在出发的时候，车的油箱是满的，并且她在路上不想加油。</span></p><p><span style="">    </span><span style="">在路上，每经过一个城市，她要交一定的费用。如果她某次交的费用比较多，她的心情就会变得很糟。所以她想知道，在她能到达目的地的前提下，她交的费用中最多的一次最少是多少。这个问题对于她来说太难了，于是她找到了聪明的你，你能帮帮她吗？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">    </span><span style="">第一行5个正整数，n，m，u，v，s。分别表示有n个城市，m条公路，从城市u到城市v，车的油箱的容量为s升。</span></p><p><span style="">    </span><span style="">接下来有n行，每行1个正整数，fi。表示经过城市i，需要交费fi元。</span></p><p><span style="">    </span><span style="">再接下来有m行，每行3个正整数，ai,bi,ci(1&lt;=ai,bi&lt;=n)。表示城市ai和城市bi之间有一条公路，如果从城市ai到城市bi,或者从城市bi到城市ai，需要用ci升汽油。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">&nbsp; &nbsp;&nbsp;</span><span style="font-family:宋体">仅一个整数，表示小红交费最多的一次的最小值。</span></p><p><span style="font-family:宋体">&nbsp;&nbsp;&nbsp; </span><span style="font-family:宋体">如果她无法到达城市v，输出-1。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【输入样例1】</span></strong></p><p><span style="">    4 4 2 3 8</span></p><p><span style="">    8</span></p><p><span style="">    5</span></p><p><span style="">    6</span></p><p><span style="">    10</span></p><p><span style="">    2 1 2</span></p><p><span style="">    2 4 1</span></p><p><span style="">    1 3 4</span></p><p><span style="">    3 4 3</span></p><p><strong><span style="">【输入样例2】</span></strong></p><p><span style="">    4 4 2 3 3</span></p><p><span style="">    8</span></p><p><span style="">    5</span></p><p><span style="">    6</span></p><p><span style="">    10</span></p><p><span style="">    2 1 2</span></p><p><span style="">    2 4 1</span></p><p><span style="">    1 3 4</span></p><p><span style="">    3 4 3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【输出样例1】</span></strong></p><p><span style="">    8</span></p><p><strong><span style="">【输出样例2】</span></strong></p><p><span style="">    -1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">    </span><span style="">对于60%的数据，满足n&lt;=200，m&lt;=10000，s&lt;=200</span></p><p><span style="">    </span><span style="">对于100%的数据，满足n&lt;=10000，m&lt;=50000，s&lt;=1000000000</span></p><p><span style="">    </span><span style="">对于100%的数据，满足ci&lt;=1000000000，fi&lt;=1000000000，可能有两条边连接着相同的城市。</span></p><p><br></p>
</div>
</div>