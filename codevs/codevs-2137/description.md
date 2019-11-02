<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>罗杰游戏由一张棋盘和‘罗杰”构成。棋盘由很多个小格组成，每个小格上刻有一个数字。l或0-255。罗杰是一个立方体，有六个面，每面上刻有一个数字1-6。这六个数字出现且仅出现一次。</p>
<p>我们开始时把罗杰放在棋盘中的一个小格上，然后让其向前、后、左、右四个方向翻滚至邻近小格中。游戏要求经过若干次翻滚后，让罗杰到达指定小格。罗杰绝对不得进入标有-1的小格，否则就会被做成烤肉串而使得我们的游戏结束。罗杰每进入一个小格后，将其顶面的数字同该小格的数字相乘，所得结果累加即得到罗杰的旅行费用。</p>
<p>开始时我们能看到罗杰的某些面上的数字，同样我们可以指定当罗杰最终到达目的格时某些面上应出现的数字。对于这些数字，我们可以任意指定。</p>
<p><strong>任务一</strong></p>
<p>在这个任务里，我们规定罗杰只能向前或向右翻滚。</p>
<p><strong>任务二</strong></p>
<p>我们将任务一扩展一下，让罗杰自由活动。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行是数字<span>1</span>或<span>2</span>，表示是任务一还是任务二。文件的第二行是两个整数<span>M</span>和<span>N</span>，给出了棋盘的列数和行数。接下来的<span>N</span>行每行表示棋盘的一行，有<span>M</span>个数，依次给出了该行上每列的数。其后的两行分别给出了罗杰的出发信息和到达信息。每行开始的两个正整数给出了罗杰所在格的列号和行号。接下来的六个数字分别表示了罗杰的顶，底，前、后、左、右各面的数字。<span>0</span>表示未知或任意。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件的第一行给出了罗杰的最小旅行费用。如果罗杰不可能按要求到达目的地，则输出<span lang="EN-US">-1</span>。否则其后每行给出了罗杰的旅行情况。从出发格到目的格，每行表示了罗杰的 一个位置，包括<span lang="EN-US">9</span>个整数，依次给出了罗杰的当前旅行费用、所在格的列编号、行编号，以及罗杰<span lang="EN-US">6</span>个面上的数字，顺序同输入文件。注意这时你的程序必须给出罗杰的完整信息，亦即各面上的数字必须是<span lang="EN-US">1-6</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>2 </span></p>
<p><span>10 10</span></p>
<p><span>1 1 1 1 1 1 1 1 1 1 </span></p>
<p><span>1 1 1 1 1 1 1 1 1 1</span></p>
<p><span>1 1 1 9 8 7 6 5 4 1</span></p>
<p><span>1 1 9 8 7 6 5 4 1 1</span></p>
<p><span>1 1 8 7 6 5 4 1 1 1</span></p>
<p><span>1 1 7 6 5 4 1 1 1 1</span></p>
<p><span>1 1 6 5 4 1 1 1 1 1</span></p>
<p><span>1 1 5 4 1 1 1 1 1 1</span></p>
<p><span>1 1 4 1 1 1 1 1 1 1</span></p>
<p><span>1 1 1 1 1 1 1 1 1 1</span></p>
<p><span>3 3 0 0 0 0 0 0</span></p>
<p><span>8 8 0 0 0 0 0 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>44</span></p>
<p><span>0 3 3 6 5 3 1 2 4</span></p>
<p><span>3 3 2 3 1 5 6 2 4</span></p>
<p><span>5 4 2 2 4 5 6 1 3</span></p>
<p><span>6 5 2 1 3 5 6 4 2</span></p>
<p><span>10 6 2 4 2 5 6 3 1</span></p>
<p><span>13 7 2 3 1 5 6 2 4</span></p>
<p><span>15 8 2 2 4 5 6 1 3</span></p>
<p><span>16 9 2 1 3 5 6 4 2</span></p>
<p><span>20 10 2 4 2 5 6 3 1</span></p>
<p><span>26 10 3 6 5 4 2 3 1</span></p>
<p><span>28 10 4 2 4 6 5 3 1</span></p>
<p><span>29 9 4 1 3 6 5 2 4</span></p>
<p><span>34 9 5 5 6 1 3 2 4</span></p>
<p><span>38 8 5 4 2 1 3 5 6</span></p>
<p><span>41 8 6 3 1 4 2 5 6</span></p>
<p><span>43 8 7 2 4 3 1 5 6</span></p>
<p><span>44 8 8 1 3 2 4 5 6</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>M，N＜40</p>
<p>不用输出完整的信息了，只输出最小旅行费用就行了</p>
</div>
</div>