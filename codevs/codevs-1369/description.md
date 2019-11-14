<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个凉爽的夏夜，xth 和 rabbit 来到花园里砍树。为啥米要砍树呢？是这样滴，<br>小菜儿的儿子窄森要出生了。Xth这个做伯伯的自然要做点什么。于是他决定带着<br>rabbit 去收集一些木材，给窄森做一个婴儿车……（xth 早就梦想着要天天打菜儿<br>他儿窄森的小 pp，到时候在婴儿车里安装一个电子遥控手臂，轻轻一按，啪啪<br>啪……“乌卡卡——”xth 邪恶滴笑了，“不要告诉 rabbit，她会说我缺德的……”<br>xth 如是说）。<br>花园里共有n棵树。为了花园的整体形象，rabbit 要求 xth只能在m个区域砍伐，我<br>们可以将这m个区域看成m个区间，树的间距相等，都是1，我们将每个区间设为<br>[x, y]。那么长度为k的区间中就有k棵树。树木的高度不等。现在 xth 想测量一下，<br>每个区间树木砍伐后所得的木材量是多少，而且每次测量后他都会砍下标号为<br>(x+y)/2<br>的那棵作为纪念。以方便他安排人手。(同一个区间的树木可以重复砍伐，我们认<br>为被砍过的树木高度为0)<br>每棵树的木材量=树的高度∗ 3.14（注意是3.14不是π）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个整数n。<br>第二行，共n个整数，表示每棵树的高度。<br>第三行，一个整数m，表示共m个区间。<br>以下m行，每个区间[x, y]的左右端点x, y。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共m行，每行一个数，表示每个区间的木材量。</p>
<p>结果精确到小数点后两位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>1 2 3 4 5<br>2<br>1 4<br>2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>31.40<br>21.98</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，有n ≤ 5000,m ≤ 5000;<br>对于100%的数据，有n ≤ 200000,m ≤ 200000;</p>
</div>
</div>