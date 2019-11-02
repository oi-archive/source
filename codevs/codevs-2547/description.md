<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">将于5月26日发售的东方辉针城在东方吧中引起了很多关注...</span></p>
<p><span style="">这个游戏是这样的，需要你操控一名角色，去和其他的杂鱼和boss决战。而对方和你的攻击的手段都是弹幕。在游戏中，你需要躲避他人的弹幕，并发射出自己的弹幕来攻击对方。本题中，为简单起见，只考虑对方发射的弹幕。</span></p>
<p>假设主角始终处于画面低端，将每秒与主角出现在一排的弹幕进行叠加，总共游戏进行了T秒，可以形成一个(T+1)×WIDTH大小的字符矩阵，“.”表示该点为空，“*”表示该点有至少一颗子弹。</p>
<p>现在告诉你主角的初始位置，求能否不中弹经过这T秒的弹幕，和操作的步骤。（主角不会⑨的）</p>
<p>题目认为抵达最后一行即视为通过，如果有多种不同的选择可以抵达最后一行请优先向左，其次不动，最后向右；题目保证数据合法且初始位置无弹幕。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入数据包括T+3行。</span><br><span>第1行为两个正整数T和WIDTH，分表表示游戏进行的时间和屏幕的宽度。</span><br><span>第2行为一个正整数S，为初始的位置。</span><br><span>第3～T+3行每行包括WIDTH个字符，表示该点的状态。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>第1行为一个字符串&ldquo;Yes&rdquo;或者&ldquo;No&rdquo;。表示能否不中弹通过此区域。</span><br /><span>第2行为一个字符串，如果出现中弹则不输出。表示通过T秒的操作，&ldquo;L&rdquo;表示向左移动一个格子，&ldquo;R&rdquo;表示向右移动一个格子，&ldquo;N&rdquo;表示不动。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>8 5</span><br><span>3</span><br><span>.....</span><br><span>.....</span><br><span>*.*.*</span><br><span>*.*.*</span><br><span>*.*.*</span><br><span>*.*.*</span><br><span>***.*</span><br><span>.....</span><br><span>.....</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>Yes</span><br><span>NRNNNNLL</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1≤T≤1000, 1≤WIDTH≤100</span></p>
<p><span>来自其他OJ, 简单题</span></p>
</div>
</div>