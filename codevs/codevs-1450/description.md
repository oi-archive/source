<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>毕业了，Xth很高兴，因为他要和他的 rabbit 去双人旅行了。他们来到了水城威尼<br>斯。众所周知（⊙﹏⊙b汗），这里的水路交通很发达，所以 xth 和 rabbit 只好坐<br>船穿梭于各个景点之间。但是要知道，rabbit 是会晕船的，看到她难受，xth 是会<br>心疼的。<br>已知城市中有n个景点，这些景点之间有m条双向水路，在每条水路上航行时<br>rabbit 都会有一个“晕船值”。旅行时，xth 会带着 rabbit 尽量选择晕船值小的路线<br>旅行。但是 rabbit 也是有一定忍耐限度度的，如果晕船值超过了她的忍耐度，xth<br>会果断决定放弃这条路线。<br>现在 xth 想进行若干次询问，给定 rabbit 的忍耐度，问还有多少对城市(x,y)间会存<br>在可行的旅行路线（如果(x,z)和(z, y)可行，则(x,y)可行，也就是说连通性是可传<br>递的）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行三个正整数n、m、q，分别表示景点数量、水路数量和询问次数。<br>第 2 行到第m + 1行每行三个正整数x、y、w，表示x号景点和y号景点之间有一条<br>“晕船值”为w的双向水路。<br>第m + 2行至第m + q + 1行，每行一个正整数k，表示询问中给定的 rabbi忍耐度<br>为k。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共q行，对于每次询问做出回答。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 2</p>
<p>1 2 1</p>
<p>2 3 2</p>
<p>3 4 1</p>
<p><span style="">4 5 4</span></p>
<p>5 1 1</p>
<p>1</p>
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
<p>4</p>
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
<p>第一个询问：(1,2), (1,5), (2,5), (3,4)。其中(2,5)的具体走法为：2 − 1 − 5<br>第二个询问：(1,2), (1,3), (1,4), (1,5), (2,3), (2,4), (2,5), (3,4), (3,5), (4,5)。其中(4,5)<br>的具体走法为：4 − 3 − 2 − 1 − 5</p>
<p>对于20%的数据满足n ≤ 20,m ≤ 40,q ≤ 40；<br>对于40%的数据满足n ≤ 1000,m ≤ 2000,q ≤ 1000；<br>对于60%的数据满足n ≤ 3000,m ≤ 6000,q ≤ 200000；<br>对于100%的数据满足n ≤ 100000,m ≤ 200000,q ≤ 200000。其他数不超过10<br>9。</p>
</div>
</div>