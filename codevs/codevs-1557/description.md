<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>德克萨斯纯朴的民眾们这个夏天正在遭受巨大的热浪！！！他们的德克萨斯长角牛吃起来不错，可是他们并不是很擅长生產富含奶油的乳製品。<span style="font-family: Times New Roman;">Farmer John</span><span style="">此时以先天下之忧而忧，后天下之乐而乐的精神，身先士卒地承担起向德克萨斯运送大量的营养冰凉的牛奶的重任，以减轻德克萨斯人忍受酷暑的痛苦。</span></p>
<p> </p>
<p>FJ<span style="">已经研究过可以把牛奶从威斯康星运送到德克萨斯州的路线。这些路线包括起始点和终点先一共经过</span><span style="font-family: Times New Roman;">T (1 &lt;= T &lt;= 2,500)</span><span style="">个城镇，方便地标号為</span><span style="font-family: Times New Roman;">1</span><span style="">到</span><span style="font-family: Times New Roman;">T</span><span style="">。除了起点和终点外地每个城镇由两条双向道路连向至少两个其它地城镇。每条道路有一个通过费用（包括油费，过路费等等）。</span></p>
<p> </p>
<p>给定一个地图，包含<span style="font-family: Times New Roman;">C (1 &lt;= C &lt;= 6,200)</span><span style="">条直接连接</span><span style="font-family: Times New Roman;">2</span><span style="">个城镇的道路。每条道路由道路的起点</span><span style="font-family: Times New Roman;">Rs</span><span style="">，终点</span><span style="font-family: Times New Roman;">Re (1 &lt;= Rs &lt;= T; 1 &lt;= Re &lt;= T)</span><span style="">，和花费</span><span style="font-family: Times New Roman;">(1 &lt;= Ci &lt;= 1,000)</span><span style="">组成。求从起始的城镇</span><span style="font-family: Times New Roman;">Ts (1 &lt;= Ts &lt;= T)</span><span style="">到终点的城镇</span><span style="font-family: Times New Roman;">Te(1 &lt;= Te &lt;= T)</span><span style="">最小的总费用。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行<span style="font-family: Times New Roman;">: 4</span><span style="">个由空格隔开的整数</span><span style="font-family: Times New Roman;">: T, C, Ts, Te</span></p>
<p>第<span style="font-family: Times New Roman;">2</span><span style="">到第</span><span style="font-family: Times New Roman;">C+1</span><span style="">行</span><span style="font-family: Times New Roman;">: </span><span style="">第</span><span style="font-family: Times New Roman;">i+1</span><span style="">行描述第</span><span style="font-family: Times New Roman;">i</span><span style="">条道路。有</span><span style="font-family: Times New Roman;">3</span><span style="">个由空格隔开的整数</span><span style="font-family: Times New Roman;">: Rs, Re</span><span style="">和</span><span style="font-family: Times New Roman;">Ci</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个单独的整数表示从Ts<span style="font-family: 宋体;">到</span><span style="font-family: Calibri;">Te</span><span style="font-family: 宋体;">的</span>最小总费用。数据保证至少存在一条道路。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 11 5 4</p>
<p>2 4 2</p>
<p>1 4 3</p>
<p>7 2 2</p>
<p>3 4 3</p>
<p>5 7 5</p>
<p>7 3 3</p>
<p>6 1 1</p>
<p>6 3 4</p>
<p>2 4 3</p>
<p>5 6 3</p>
<p>7 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>5-&gt;6-&gt;1-&gt;4 (3 + 1 + 3)</p>
</div>
</div>