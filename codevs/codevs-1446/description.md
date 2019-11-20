<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了表彰小联为<strong><em>Samuel</em></strong>星球的探险所做出的贡献，小联被邀请参加<strong><em>Samuel</em></strong>星球近距离载人探险活动。</p>
<p>由于<strong><em>Samuel</em></strong>星球相当遥远，科学家们要在飞船中度过相当长的一段时间，小联提议用扑克牌打发长途旅行中的无聊时间。玩了几局之后，大家觉得单纯玩扑克牌对于像他们这样的高智商人才来说太简单了。有人提出了扑克牌的一种新的玩法。</p>
<p>对于扑克牌的一次洗牌是这样定义的，将一叠N（N为偶数）张扑克牌平均分成上下两叠，取下面一叠的第一张作为新的一叠的第一张，然后取上面一叠的第一张作为新的一叠的第二张，再取下面一叠的第二张作为新的一叠的第三张……如此交替直到所有的牌取完。</p>
<p>如果对一叠6张的扑克牌1 2 3 4 5 6，进行一次洗牌的过程如下图所示：</p>
<p> </p>
<p>从图中可以看出经过一次洗牌，序列1 2 3 4 5 6变为4 1 5 2 6 3。当然，再对得到的序列进行一次洗牌，又会变为2 4 6 1 3 5。</p>
<p>游戏是这样的，如果给定长度为N的一叠扑克牌，并且牌面大小从1开始连续增加到N（不考虑花色），对这样的一叠扑克牌，进行M次洗牌。最先说出经过洗牌后的扑克牌序列中第L张扑克牌的牌面大小是多少的科学家得胜。小联想赢取游戏的胜利，你能帮助他吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中有三个用空格间隔的整数，分别表示N，M，L</p>
<p>（其中0＜N≤10<sup>10</sup> ，0 ≤M≤10<sup>10</sup>，且N为偶数）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>单行输出指定的扑克牌的牌面大小。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>