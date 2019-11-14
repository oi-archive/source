<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       在小松宿舍楼下的不远处，有PK大学最不错的一个食堂——The Farmer’s Canteen（NM食堂）。由于该食堂的菜都很不错，价格也公道，所以很多人都喜欢来这边吃饭。The Farmer’s Canteen的点菜方式如同在超市自选商品一样，人们从一个指定的路口进去，再从一个指定的路口出来并付款。由于来这里就餐的人数比较多，所以人们自觉地在进入口的时候就排成一个长队，沿着长长的摆放着各式各样佳肴的桌子进行选菜。</p>
<p>       小松发现，这种选菜方式意味着，他不能在选菜的时候离开队伍去拿一些他已经看过了的菜或者没有看过的菜，因为插队是不礼貌的，也是被BS的。</p>
<p>       每个菜有一个价值，而小松也自己给每个菜定了一个在他看来的美味价值，例如红烧小黄鱼在小松看来是美味价值很高的，而花菜在小松眼里则是美味价值极低的菜肴。而有一些菜是营养价值极其高的菜（例如米饭），所以无论它的美味价值是多少，小松都会选择1份。现在小松带了<em>X</em>元钱来食堂就餐，他想知道，在<strong>不欠帐</strong>的情况下，他选菜的美味价值总合最大是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       请从输入文件farmer.in中读入相关数据。输入的第一行包括两个个整数<em>n</em>（1<em>≤n</em><em>≤</em>100），<em>k</em>（0<em>≤</em><em>k</em><em>≤</em>实际菜的种类）和一个实数<em>X</em>（0<em>≤X</em><em>≤</em>100），表示有<em>n</em>个菜式，有<em>k</em>种菜是必选的，小松带来了<em>X</em>元钱（精确到“角”）。接下来的1行包含<em>n</em>个实数，表示菜桌上从入口到出口的所有菜的价格（0<em>≤</em>价格<em>≤</em>10，单位“元”，精确到“角”）；再接下来的1行包含<em>n</em>个整数，表示菜桌上从入口到出口的所有菜的美味价值（0<em>≤</em>美味价值<em>≤</em>100）；再接下来一行包含<em>n</em>个整数，表示菜桌上从入口到出口的所有菜的种类编号（1<em>≤</em>种类编号<em>≤</em>100）。最后一行包含<em>k</em>个整数<strong>，</strong>分别表示必选菜的<strong>种类编号</strong>。<span style="text-decoration: underline;">要注意的是，同一种编号的菜可以出现多次，但是他们的价格和美味价值都是一样的。对于同一种菜（无论是不是必选菜），小松最多只会选择</span><span style="text-decoration: underline;">1</span><span style="text-decoration: underline;">份（买两份红烧豆腐多没意思啊）。另外，必选菜的价格之和一定不超过<em>X</em></span><em><span style="text-decoration: underline;">。</span></em></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp; &nbsp; &nbsp;&nbsp;请将结果输出到输出文件farmer.out中。输出包含一个整数，表示小松能选到的菜的美味价值总和最大是多少。</p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>注：你可以假设数据中不会出现小松带的钱不够买必买菜的情况。</strong></p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 1 5.0</p>
<p>4 1 3 0.9 2 0.5 0.9</p>
<p>7 3 5 2 5 0 2</p>
<p>6 3 5 2 4 1 2</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>