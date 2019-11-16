<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>淘汰赛制是一种极其残酷的比赛制度。<span style="font-family: 'Times New Roman';">2n</span><span style="">名选手分别标号</span><span style="font-family: 'Times New Roman';">1</span><span style="">，</span><span style="font-family: 'Times New Roman';">2</span><span style="">，</span><span style="font-family: 'Times New Roman';">3</span><span style="">，…</span><span style="font-family: 'Times New Roman';">2n-1</span><span style="">，</span><span style="font-family: 'Times New Roman';">2n</span><span style="">，他们将要参加</span><span style="font-family: 'Times New Roman';">n</span><span style="">轮的激烈角逐。每一轮中，将所有参加该轮的选手按标号从小到大排序后，第</span><span style="font-family: 'Times New Roman';">1</span><span style="">位与第</span><span style="font-family: 'Times New Roman';">2</span><span style="">位比赛，第</span><span style="font-family: 'Times New Roman';">3</span><span style="">位与第</span><span style="font-family: 'Times New Roman';">4</span><span style="">位比赛，第</span><span style="font-family: 'Times New Roman';">5</span><span style="">位与第</span><span style="font-family: 'Times New Roman';">6</span><span style="">位比赛……只有每场比赛的胜者才有机会参加下一轮的比赛（不会有平局）。这样，每轮将淘汰一半的选手。</span><span style="font-family: 'Times New Roman';">n</span><span style="">轮过后，只剩下一名选手，该选手即为最终的冠军。</span></p>
<p>现在已知每位选手分别与其他选手比赛获胜的概率，请你预测一下谁夺冠的概率最大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件<span style="font-family: 'Times New Roman';">elimination.in</span><span style="">。第一行是一个整数</span><span style="font-family: 'Times New Roman';">n</span><span style="">（</span><span style="font-family: 'Times New Roman';">1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">10</span><span style="">），表示总轮数。接下来</span><span style="font-family: 'Times New Roman';">2n</span><span style="">行，每行</span><span style="font-family: 'Times New Roman';">2n</span><span style="">个整数，第</span><span style="font-family: 'Times New Roman';">i</span><span style="">行第</span><span style="font-family: 'Times New Roman';">j</span><span style="">个是</span><span style="font-family: 'Times New Roman';">Pij0</span><span style="">≤</span><span style="font-family: 'Times New Roman';">Pij</span><span style="">≤</span><span style="font-family: 'Times New Roman';">100</span><span style="">，</span><span style="font-family: 'Times New Roman';">Pii=0</span><span style="">，</span><span style="font-family: 'Times New Roman';">Pij+Pji=100</span><span style="">），表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">号选手与第</span><span style="font-family: 'Times New Roman';">j</span><span style="">号选手比赛获胜的概率。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件<span style="font-family: 'Times New Roman';">elimination.out</span><span style="font-family: 宋体;">。只有一个整数</span><span style="font-family: 'Times New Roman';">c,</span><span style="font-family: 宋体;">表示夺冠概率最大的选手编号（若有多位选手，输出编号最小者）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>0 90 50 50</p>
<p>10 0 10 10</p>
<p>50 90 0 50</p>
<p>50 90 50 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>[<span style="">数据规模</span><span style="font-family: 'Times New Roman';">]</span></p>
<p>30%<span style="">的数据满足</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">3</span><span style="">；</span></p>
<p>100%<span style="">的数据满足</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">10</span><span style="">。</span></p>
</div>
</div>