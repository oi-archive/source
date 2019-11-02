<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个这样的单人游戏：在一个10*15的棋盘上，每个格子可以放红、绿、蓝色的小球。</p>
<p>如果两个球有同样的颜色，而且它们在棋盘上是相连的，那么它们属于同一块。在游戏的每一步，玩家选择可以选择至少两个连成一块的球，然后其余的小球棋盘这样靠拢：</p>
<p>1．  在每一列的剩下的棋子都往下挤，而且保持顺序不变。</p>
<p>2．如果某一列是空的，则将右边一列向左移。</p>
<p>如果能将棋盘中的所有小球全部拿出，则胜利，否则失败。计分的方式如下：开始时，得分为0。每拿出有<em>m</em>个球的块，得分增加(m-2)<sup>2</sup>。如果所有的球全部都被拿出，则另外奖励1000分。现在，需要你来编一个程序来模拟一次游戏。每次都选择连成块最多的，如果有多个，则选择最左边的那一列最靠下的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共有10行，每行15个字符（“R”、“G”、“B”中的一种），代表所在位置的颜色。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>有两个整数，即最后的得分，以及最终剩下的小球个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>RGGBBGGRBRRGGBG</p>
<p>RBGRBGRBGRBGRBG</p>
<p>RRRRGBBBRGGRBBB</p>
<p>GGRGBGGBRRGGGBG</p>
<p>GBGGRRRRRBGGRRR</p>
<p>BBBBBBBBBBBBBBB</p>
<p>BBBBBBBBBBBBBBB</p>
<p>RRRRRRRRRRRRRRR</p>
<p>RRRRRRGGGGRRRRR</p>
<p>GGGGGGGGGGGGGGG</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3661 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>10*15</p>
</div>
</div>