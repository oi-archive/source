<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="">奶牛们以它们一贯笨拙的方式玩</span>Yahtzee，一种掷骰子的游戏。他们掷N 次(1 ≤ N ≤ 20) S(1 ≤ S ≤ 8)面骰子。他们对于能满足一定标准的掷出骰子的结果的数量很感兴趣（类似“包含3个2”或者“包含一个2和两个3”）。</span></p><p style=""><span style=""><span style="">教他们学会概率。写一个程序，不仅读入</span>N和S，而且还有一些说明这些标准的表达式。从骰子的所有可能的组合中找出符合表达式要求的组合的数量（3个2面骰子所有可能的组合是 {1,1,1; 1,1,2; 1,2,1; 1,2,2; 2,1,1; 2,1,2;2,2,1; 2,2,2};）。</span></p><p style=""><span style=""><span style="">这种组合的最基本的形式表达了</span>“希望至少有W份R”看上去像这样：</span></p><p style=""><span style="">WxR</span></p><p style=""><span style=""><span style="">这里满足</span>(0 ≤ W ≤ N and 1 ≤ R ≤ S)。每次检验运行提供E个表达式(1 ≤ E ≤ 20)，每个包含1~10个由“+”分割的基本形式。“+”表示“且”(看下面)。行与行之间的关系是“或者”。这样，下面所示的表达式的意思是：</span></p><p style=""><span style="">“至少有三个5 *或者* 同时至少有1个3和至少2个4”：</span></p><p style=""><span style="">3x5</span></p><p style=""><span style="">1x3+2x4</span></p><p style=""><span style=""><span style="">这里有一些满足上述条件的</span>4个5面骰可能的情况：5,5,5,1; 4,5,5,5; 3,4,4,2;</span></p><p style=""><span style="">3,4,4,3;3,4,4,5; 4,4,5,3。</span></p><p style=""><span style=""><span style="">注意：确保你能从一行中读取</span>2个整数并在下一行中能读取一个字符串。对有某些语言的I/O设计来说，这比看上去的更难。</span></p><p style=""><span style=""><span style="">同时注意所有骰子可能的组合数在提供的测试数据里不会超过</span>1,512,768。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">第</span> 1 行: 三个由空格分开的整数: N, S 和 E</span></p><p><span style=""><span style="">第</span> 2 至 E+1 行: 第i+1 描述第i个表达式</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:16px"><span style="font-family:宋体">一行</span>: <span style="font-family:宋体">一个整数，从骰子的所有可能的组合中找出符合表达式要求的组合的数量</span></span></p><p><br/></p><p><br/></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 5 2</span></p><p><span style="">3x5</span></p><p><span style="">1x3+2x4</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">63</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">(1 ≤ N ≤ 20)</span><span style="">；</span><span style=""> </span></p><p><span style="">S(1 ≤ S ≤ 8)</span><span style="">；</span></p><p><span style="">(1 ≤ E ≤ 20)</span></p><p><br></p>
</div>
</div>