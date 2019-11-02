<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明过生日的时候，爸爸送给他一副乌龟棋当作礼物。 乌龟棋的棋盘是一行N个格子，每个格子上一个分数（非负整数）。棋盘第1格是唯一 的起点，第N格是终点，游戏要求玩家控制一个乌龟棋子从起点出发走到终点。</p>
<p>…… 1 2 3 4 5 ……N 乌龟棋中M张爬行卡片，分成4种不同的类型（M张卡片中不一定包含所有4种类型 的卡片，见样例），每种类型的卡片上分别标有1、2、3、4四个数字之一，表示使用这种卡 片后，乌龟棋子将向前爬行相应的格子数。游戏中，玩家每次需要从所有的爬行卡片中选择 一张之前没有使用过的爬行卡片，控制乌龟棋子前进相应的格子数，每张卡片只能使用一次。 游戏中，乌龟棋子自动获得起点格子的分数，并且在后续的爬行中每到达一个格子，就得到 该格子相应的分数。玩家最终游戏得分就是乌龟棋子从起点到终点过程中到过的所有格子的 分数总和。 很明显，用不同的爬行卡片使用顺序会使得最终游戏的得分不同，小明想要找到一种卡 片使用顺序使得最终游戏得分最多。 现在，告诉你棋盘上每个格子的分数和所有的爬行卡片，你能告诉小明，他最多能得到 多少分吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的每行中两个数之间用一个空格隔开。 第1行2个正整数N和M，分别表示棋盘格子数和爬行卡片数。 第2行N个非负整数，a1a2……aN</p>
<p>，其中ai表示棋盘第i个格子上的分数。 第3行M个整数，b1b2……bM</p>
<p>，表示M张爬行卡片上的数字。 输入数据保证到达终点时刚好用光M张爬行卡片，即N - 1=∑(1-&gt;M) b<sub>i</sub></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行一个整数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">13 8</span></p>
<p style=""><span style="font-family: 'Courier New';">4 96 10 64 55 13 94 53 5 24 89 8 30</span></p>
<p style=""><span style="font-family: 'Courier New';">1 1 1 1 1 2 4 1</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">455</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【数据范围】</span></p>
<p style=""><span style="">对于</span><span style="font-family: 'TimesNewRomanPSMT';">30%</span><span style="">的数据有</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">N</span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">30</span><span style="">，</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'TimesNewRomanPSMT';">M</span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">12</span><span style="">。</span></p>
<p style=""><span style="">对于</span><span style="font-family: 'TimesNewRomanPSMT';">50%</span><span style="">的数据有</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">N</span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">120</span><span style="">，</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'TimesNewRomanPSMT';">M</span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">50</span><span style="">，且</span><span style="font-family: 'TimesNewRomanPSMT';">4 </span><span style="">种爬行卡片，每种卡片的张数不会超</span></p>
<p style=""><span style="">过</span><span style="font-family: 'TimesNewRomanPSMT';">20</span><span style="">。</span></p>
<p style=""><span style="">对于</span><span style="font-family: 'TimesNewRomanPSMT';">100%</span><span style="">的数据有</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">N</span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">350</span><span style="">，</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'TimesNewRomanPSMT';">M</span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">120</span><span style="">，且</span><span style="font-family: 'TimesNewRomanPSMT';">4 </span><span style="">种爬行卡片，每种卡片的张数不会</span></p>
<p style=""><span style="">超过</span><span style="font-family: 'TimesNewRomanPSMT';">40</span><span style="">；</span><span style="font-family: 'TimesNewRomanPSMT';">0 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">a</span><span style="font-family: 'TimesNewRomanPSMT';">i </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">100</span><span style="">，</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">i </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">N</span><span style="">；</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">b</span><span style="font-family: 'TimesNewRomanPSMT';">i </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">4</span><span style="">，</span><span style="font-family: 'TimesNewRomanPSMT';">1 </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'SymbolMT';"> </span><span style="font-family: 'TimesNewRomanPSMT';">i </span><span style="font-family: 'SymbolMT';">≤</span><span style="font-family: 'TimesNewRomanPSMT';">M</span><span style="">。输入数据保证</span><span style="font-family: 'TimesNewRomanPSMT';">N−1=</span><span style="font-family: 'SymbolMT';">Σ</span><span style="font-family: 'Times New Roman';">M</span></p>
<p style=""><span style="font-family: 'Times New Roman';">i </span><span style="font-family: 'Times New Roman';">b</span></p>
<p style=""><span style="font-family: 'TimesNewRomanPSMT';">1</span></p>
<!--EndFragment-->
</div>
</div>