<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小鱼儿是个数学天才。一天晚上他研究一个和字符串有关的penney-ante游戏。游戏的规则如下：</p>
<p>1．有两个玩家，开始时每人选择一个长度相同的字符串；</p>
<p>2．一个字符生成器不断的随机生成字母添加到字符串<em>S</em>的末尾，<em>S</em>初始为空串；</p>
<p>3．如果<em>S</em>包含了某个玩家选择的字符串则游戏结束，该玩家获胜。</p>
<p> </p>
<p>假设玩家1和玩家2分别选择了两个字符串<em>A</em>和<em>B</em>，<span style="text-decoration: underline;">如果玩家</span><span style="text-decoration: underline;">1</span><span style="text-decoration: underline;">可以以较大概率战胜玩家</span><span style="text-decoration: underline;">2</span><span style="text-decoration: underline;">，</span>我们记作<em><span style="text-decoration: underline;">A</span></em><span style="text-decoration: underline;">&gt;<em>B</em></span>。 咋一看来，小鱼儿觉得如果<em>A</em>&gt;<em>B</em>且<em>B</em>&gt;<em>C</em>则<em>A</em>&gt;<em>C</em>。可事实恰好相反，存在字符串<em>A</em>, <em>B</em>, <em>C</em>使得<em>A</em>&gt;<em>B</em>, <em>B</em>&gt;<em>C</em>, <em>C</em>&gt;<em>A</em>。</p>
<p> </p>
<p>小鱼儿被这种戏的一个<strong>反常现象</strong>所吸引，通过查阅资料，他了解到这种现象被称为“<strong>非传递性悖论</strong>”，在许多非完全信息游戏（比如军棋）中，经常会有这样的例子。可是它到底是如何产生的呢？小鱼儿决定设计一种游戏，从中可以容易的找到非传递的例子，以便更清楚的认识“<em>非传递性</em>”。当然，这样的游戏越简单道理越深刻，于是小鱼儿想起了最简单的掷骰子游戏……</p>
<p> </p>
<p>这个游戏是这样的，假设有<em>n</em>个骰子<em>D</em><sub>1</sub>~<em>D<sub>n</sub></em>，每个骰子有<em>m</em>个面。每个面上标有一个1~<em>n</em>×<em>m</em>的正整数，并且所有骰子的所有<em>n</em>×<em>m</em>个面上的数字各不相同。满足这条编号要求，并且每个面被随到的概率相等的，这样的<em>n</em>个骰子称为一组“好骰子”。游戏开始时，两个玩家分别选两个骰子<em>D<sub>i</sub></em>和<em>D<sub>j</sub></em>，各掷一次来比较掷出来那一面的数值，数大的获胜。</p>
<p> </p>
<p>小鱼儿请你帮忙设计一组“好骰子”，使得对任意一个骰子<em>D<sub>i</sub></em>，它总能<strong>战胜</strong><em>D<sub>ai</sub></em>。此处战胜是指选择前者的玩家获胜的<strong>概率超过</strong>1/2；<em>a</em><sub>1</sub>~<em>a<sub>n</sub></em>为输入的1~<em>n</em>的正整数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数<em>n</em>, <em>m</em>。第二行有<em>n</em>个整数，为<em>a</em><sub>1</sub>，<em>a</em><sub>2</sub>, …, <em>a<sub>n</sub></em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含<em>n</em>行，每行<em>m</em>个1~<em>n</em>&times;<em>m</em>的正整数，各不相同，以空格分开。</p>
<p>如果有多解，输出任意一组解；如果无解，输出一个整数0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p>
<p>4 1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 11 8 14</p>
<p>12 15 2 5</p>
<p>3 6 16 9</p>
<p>4 10 13 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据满足<em>n</em>, <em>m</em>≤10</p>
<p>100%的数据满足3≤<em>n</em>, <em>m</em>≤200</p>
</div>
</div>