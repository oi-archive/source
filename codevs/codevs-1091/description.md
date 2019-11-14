<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">【问题背景】</p>
<p style="">近来，一种新的传染病肆虐全球。蓬莱国也发现了零星感染者，为防止该病在蓬莱国</p>
<p style="">大范围流行，该国政府决定不惜一切代价控制传染病的蔓延。不幸的是，由于人们尚未完</p>
<p style="">全认识这种传染病，难以准确判别病毒携带者，更没有研制出疫苗以保护易感人群。于是，</p>
<p style="">蓬莱国的疾病控制中心决定采取切断传播途径的方法控制疾病传播。经过 <span style="font-family: DejaVu Serif Condensed,serif;">WHO</span>（世界卫</p>
<p style="">生组织）以及全球各国科研部门的努力，这种新兴传染病的传播途径和控制方法已经研究</p>
<p style="">消楚，剩下的任务就是由你协助蓬莱国疾控中心制定一个有效的控制办法。</p>
<p style=""> </p>
<p style="">【问题描述】</p>
<p style="">研究表明，这种传染病的传播具有两种很特殊的性质；</p>
<p style="">第一是它的传播途径是树型的，一个人<span style="font-family: DejaVu Serif Condensed,serif;">X</span>只可能被某个特定的人<span style="font-family: DejaVu Serif Condensed,serif;">Y</span>感染，只要<span style="font-family: DejaVu Serif Condensed,serif;">Y</span>不</p>
<p style="">得病，或者是<span style="font-family: DejaVu Serif Condensed,serif;">XY</span>之间的传播途径被切断，则<span style="font-family: DejaVu Serif Condensed,serif;">X</span>就不会得病。</p>
<p style="">第二是，这种疾病的传播有周期性，在一个疾病传播周期之内，传染病将只会感染一</p>
<p style="">代患者，而不会再传播给下一代。</p>
<p style="">这些性质大大减轻了蓬莱国疾病防控的压力，并且他们已经得到了国内部分易感人群</p>
<p style="">的潜在传播途径图（一棵树）。但是，麻烦还没有结束。由于蓬莱国疾控中心人手不够，同</p>
<p style="">时也缺乏强大的技术，以致他们在一个疾病传播周期内，只能设法切断一条传播途径，而</p>
<p style="">没有被控制的传播途径就会引起更多的易感人群被感染（也就是与当前已经被感染的人有</p>
<p style="">传播途径相连，且连接途径没有被切断的人群）。当不可能有健康人被感染时，疾病就中止</p>
<p style="">传播。所以，蓬莱国疾控中心要制定出一个切断传播途径的顺序，以使尽量少的人被感染。</p>
<p style="">你的程序要针对给定的树，找出合适的切断顺序。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""> </p>
<p style="">输入格式的第一行是两个整数<span style="font-family: DejaVu Serif Condensed,serif;">n</span>（<span style="font-family: DejaVu Serif Condensed,serif;">1≤n≤300</span>）和<span style="font-family: DejaVu Serif Condensed,serif;">p</span>。接下来<span style="font-family: DejaVu Serif Condensed,serif;">p</span>行，每一行有两个整数<span style="font-family: DejaVu Serif Condensed,serif;">i</span></p>
<p style=""> </p>
<p style="">和<span style="font-family: DejaVu Serif Condensed,serif;">j</span>，表示节点<span style="font-family: DejaVu Serif Condensed,serif;">i</span>和<span style="font-family: DejaVu Serif Condensed,serif;">j</span>间有边相连（意即，第<span style="font-family: DejaVu Serif Condensed,serif;">i</span>人和第<span style="font-family: DejaVu Serif Condensed,serif;">j</span>人之间有传播途径相连）。其中节点</p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1</span>是已经被感染的患者。</p>
<p style=""><span style=""><br></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">只有一行，输出总共被感染的人数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">7 6</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 2</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 3</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2 4</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2 5</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3 6</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3 7</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=300</p>
</div>
</div>