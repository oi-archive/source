<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>话说数年一度的武林盛事“华山论剑”将至，东邪、西毒、南帝、北丐，老顽童等高手云集华山之巅，誓要分出究竟谁是武林至尊</p><p><span style="">如此武林盛世，当然求围观。据统计，有n-1位同学想去华山看热闹，他们分别住在编号为1-n(除华山所在地x)的地方，华山编号为x(1&lt;=x&lt;=n)。现在有M(1&lt;=m&lt;=100000)条有向道路，每条路长为ti(1&lt;=ti&lt;=1000)。</span></p><p style=""><span style="">由于每位同学看完打架后还要回家吃饭，所以要选择最短路径，求这n-1位同学的最短路径（一个来回）中最长的一条的长度。</span></p><p style=""><span style="">特别提醒：可能有权值不同的重边。</span></p><p><span style="">数据保证每位同学均能到达华山处，并从华山返回</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第1行： n,m,x；</span></p><p style=""><span style="">第2~m+1行: ai,bi,ti,表示有一条从ai到bi的路，长度为ti.</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体">输出仅一行，为最长最短路的长度。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">4 8 2</span></p><p style=""><span style="">1 2 4</span></p><p style=""><span style="">1 3 2</span></p><p style=""><span style="">1 4 7</span></p><p style=""><span style="">2 1 1</span></p><p style=""><span style="">2 3 5</span></p><p style=""><span style="">3 1 2</span></p><p style=""><span style="">3 4 4</span></p><p style=""><span style="">4 2 3</span></p><p><br></p>

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
<p style=""><span style="">对于50%的数据，满足 1&lt;=n&lt;=100，1&lt;=m&lt;=10000</span></p><p><span style="">　　对于100%的数据，满足 1&lt;=n&lt;=1000,1&lt;=m&lt;=100000。</span></p><p><br></p>
</div>
</div>