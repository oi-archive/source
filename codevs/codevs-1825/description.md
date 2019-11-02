<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某个国家有<span style="font-family: 'Times New Roman';">n</span><span style="">个城市，这</span><span style="font-family: 'Times New Roman';">n</span><span style="">个城市中任意两个都连通且有唯一一条路径，每条连通两个城市的道路的长度为</span><span style="font-family: 'Times New Roman';">zi(zi&lt;=1000)</span><span style="">。</span></p>
<p>这个国家的人对火焰有超越宇宙的热情，所以这个国家最兴旺的行业是消防业。由于政府对国民的热情忍无可忍（大量的消防经费开销）可是却又无可奈何（总统竞选的国民支持率），所以只能想尽方法提高消防能力。</p>
<p>现在这个国家的经费足以在一条边长度和不超过<span style="font-family: 'Times New Roman';">s</span><span style="">的路径（两端都是城市）上建立消防枢纽，为了尽量提高枢纽的利用率，要求其他所有城市到这条路径的距离的最大值最小。</span></p>
<p>你受命监管这个项目，你当然需要知道应该把枢纽建立在什么位置上。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入包含<span style="font-family: 'Times New Roman';">n</span><span style="">行：</span><br>    第<span style="font-family: 'Times New Roman';">1</span><span style="">行，两个正整数</span><span style="font-family: 'Times New Roman';">n</span><span style="">和</span><span style="font-family: 'Times New Roman';">s</span><span style="">，中间用一个空格隔开。其中</span><span style="font-family: 'Times New Roman';">n</span><span style="">为城市的个数，</span><span style="font-family: 'Times New Roman';">s</span><span style="">为路径长度的上界。设结点编号以此为</span><span style="font-family: 'Times New Roman';">1</span><span style="">，</span><span style="font-family: 'Times New Roman';">2</span><span style="">，</span><span style="font-family: 'Times New Roman';">……</span><span style="">，</span><span style="font-family: 'Times New Roman';">n</span><span style="">。</span><br>  <span style="">从第</span><span style="font-family: 'Times New Roman';">2</span><span style="">行到第</span><span style="font-family: 'Times New Roman';">n</span><span style="">行，每行给出</span><span style="font-family: 'Times New Roman';">3</span><span style="">个用空格隔开的正整数，依次表示每一条边的两个端点编号和长度。例如，</span><span style="font-family: 'Times New Roman';">“2 4 7”</span><span style="">表示连接结点</span><span style="font-family: 'Times New Roman';">2</span><span style="">与</span><span style="font-family: 'Times New Roman';">4</span><span style="">的边的长度为</span><span style="font-family: 'Times New Roman';">7</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p15">输出包含一个非负整数，即所有城市到选择的路径的最大值，当然这个最大值必须是所有方案中最小的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入<span style="font-family: Arial;">1</span><span style="">】</span></p>
<p>5 2<br>1 2 5<br>2 3 2<br>2 4 4<br>2 5 3 </p>
<p>【样例输入<span style="font-family: Arial;">2</span><span style="">】</span></p>
<p>8 6<br>1 3 2<br>2 3 2 <br>3 4 6<br>4 5 3<br>4 6 4<br>4 7 2<br>7 8 3  </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出<span style="font-family: 'Times New Roman';">1</span><span style="">】</span></p>
<p>5</p>
<p>【样例输出<span style="font-family: Arial;">2</span><span style="">】</span></p>
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n&lt;=300</span><span style="">。</span></p>
<p>对于<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n&lt;=3000</span><span style="">。</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n&lt;=300000</span><span style="">，边长小等于</span><span style="font-family: 'Times New Roman';">1000</span><span style="">。 </span></p>
</div>
</div>