<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">TNT机器人比赛就要开始了，小明也参加了，正准备出发，麻烦出现了。校车太小了！小明急得团团转，无奈之下他只好买了一个箱子，箱子分为四格，分别装铁片，马达，小零件和遥控器。</span><span style="text-decoration: underline;"><strong><span style="">装铁片的一格可装铁片</span>AMAX cm<span style="">³，装马达的一格可装马达</span>BMAX cm<span style="">³，装小零件的一格可装小零件</span>CMAX cm<span style="">³，装遥控器的一格可装遥控器</span>DMAX cm<span style="">³。现在有</span>N<span style="">盒零件，每盒零件有铁片</span>A cm³,<span style="">有马达</span>B cm³,<span style="">有小零件</span>C cm³,<span style="">有遥控器</span>D cm³<span style="">，每盒零件的价值为</span>V<span style="">元。</span></strong></span><span style="">价值越高质量就越好，</span><span style=""><strong>各种零件总体积不得超过此零件一个的容积</strong></span><span style="">。因为时间关系，</span><strong><span style="text-decoration: underline;"><span style="">小明只能选择</span>X<span style="">盒（必须为整数盒）</span></span></strong><span style="">，倒进箱子中，小明希望</span><strong><span style="">总价值最大</span></strong><span style="">（</span><span style=""><em>小明有1000000<sup>n</sup>元,不怕钱不够 n&gt;10</em></span><span style="">），这样机器人的性能就越好（</span><span style=""><em>不好会被TNT炸掉，不合算——反正用的不是你的钱</em></span><span style="">）。小明能选择的最大价值是多少呢？</span></p><p> <span style=""></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行五个整数，</span>N,AMAX,BMAX,CMAX<span style="">和</span>DMAX<span style="">，表示零件的数量，铁片一格的空间，马达一格的空间，小零件的空间，遥控器一格的空间。</span></p><p style=""><span style="">接下来</span>N<span style="">行，每行五个整数</span>A<span style="">、</span>B<span style="">、</span>C<span style="">、</span>D<span style="">、</span>V<span style="">表示一盒零件中铁片、马达、小零件、遥控器的体积和这盒零件的价格。</span></p><p style=""> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体">输出小明能选择的最大价值</span><span style=";font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 2 2 2 2</span></p><p><span style="">1 0 1 0 5</span></p><p><span style="">0 1 0 1 10</span></p><p><span style="">1 1 1 1 1</span></p><p><span style="">0 0 0 0 0</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">16</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例解释】</span></p><p style=""><span style="">选价值为</span>5<span style="">、</span>10<span style="">、</span>1<span style="">的三盒，四种零件分别占体积</span>1+0+1=2<span style="">、</span>0+1+1=2<span style="">、</span>1+0+1=2<span style="">、</span>0+1+1=2<span style="">，正好填满箱子，总价值为</span>5+10+1=16<span style="">元。</span></p><p><span style="">【数据范围】</span></p><p style=""><span style="font-family: 'Times New Roman','serif';"></span><span style="font-family: 'Times New Roman','serif';">10%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman','serif';">N=1,1&lt;=</span><span style="font-family: 'Times New Roman','serif';">AMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">BMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">CMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">DMAX &lt;=2,<span style='font-family: "Times New Roman", serif;'>0&lt;=</span><span style='font-family: "Times New Roman", serif;'>A</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>B</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>C</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>D &lt;=2,0&lt;=V&lt;=100</span></span><span style="font-family: 'Times New Roman','serif';"></span></p><p style=""><span style="font-family: 'Times New Roman','serif';">60%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman','serif';">1&lt;=N&lt;=20,1&lt;=</span><span style="font-family: 'Times New Roman','serif';">AMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">BMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">CMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">DMAX &lt;=18,<span style='font-family: "Times New Roman", serif;'>0&lt;=</span><span style='font-family: "Times New Roman", serif;'>A</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>B</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>C</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>D &lt;=18,0&lt;=V&lt;=100</span></span></p><p style=""><span style="font-family: 'Times New Roman','serif';"><span style='font-family: "Times New Roman", serif;'><span style="font-family: 'Times New Roman','serif';">100%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman','serif';">1&lt;=N&lt;=32,1&lt;=</span><span style="font-family: 'Times New Roman','serif';">AMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">BMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">CMAX</span><span style="">、</span><span style="font-family: 'Times New Roman','serif';">DMAX &lt;=18,<span style='font-family: "Times New Roman", serif;'>0&lt;=</span><span style='font-family: "Times New Roman", serif;'>A</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>B</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>C</span><span style="">、</span><span style='font-family: "Times New Roman", serif;'>D &lt;=18,0&lt;=V&lt;=100</span></span></span></span></p><p><br></p>
</div>
</div>