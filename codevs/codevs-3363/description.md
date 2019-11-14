<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>宅男</span><span>JYY</span><span>非常喜欢玩</span><span>RPG</span><span>游戏，比如仙剑，轩辕剑等等。不过</span><span>JYY</span><span>喜欢的并不是战斗场景，而是类似电视剧一般的充满恩怨情仇的剧情。这些游戏往往都有很多的支线剧情，现在</span><span>JYY</span><span>想花费最少的时间看完所有的支线剧情。 </span></p>
<p><span>JYY</span><span>现在所玩的</span><span>RPG</span><span>游戏中，一共有</span><span>N</span><span>个剧情点，由</span><span>1</span><span>到</span><span>N</span><span>编号，第</span><span>i</span><span>个剧情点可以根据</span><span>JYY</span><span>的不同的选择，而经过不同的支线剧情，前往 </span><span>K</span><span>i</span><span>种不同的新的剧情点。当然如果 </span><span>K</span><span>i</span><span> 为</span><span>0</span><span>，则说明</span><span>i</span><span>号剧情点是游戏的一个结局了。 </span></p>
<p><span>JYY</span><span>观看一个支线剧情需要一定的时间。 </span></p>
<p><span>JYY</span><span>一开始处在</span><span>1</span><span>号剧情点，也就是游戏的开始。 </span></p>
<p><span>显然任何一个剧情点都是从</span><span>1</span><span>号剧情点可达的。此外，随着游戏的进行，剧情是不可逆的。所以游戏保证从任意剧情点出发，都不能再回到这个剧情点。 </span></p>
<p><span>由于</span><span>JYY</span><span>过度使用修改器，导致游戏的</span><span>“</span><span>存档</span><span>”</span><span>和</span><span>“</span><span>读档</span><span>”</span><span>功能损坏了，所以</span><span>JYY</span><span>要想回到之前的剧情点，唯一的方法就是退出当前游戏，并开始新的游戏，也就是回到</span><span>1</span><span>号剧情点。</span><span>JYY</span><span>可以在任何时刻退出游戏并重新开始。 </span></p>
<p><span>不断开始新的游戏重复观看已经看过的剧情是很痛苦，</span><span>JYY</span><span>希望花费最少的时间，看完所有不同的支线剧情。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入一行包含一个正整数</span><span>N</span><span>。 </span></p>
<p><span>接下来</span><span>N</span><span>行，第</span><span>i</span><span>行为</span><span>i</span><span>号剧情点的信息； </span></p>
<p><span>第一个整数为 </span><span>K</span><span>i</span><span> ，接下来 </span><span>K</span><span>i</span><span> 个整数对，</span><span>b</span><span>ij</span><span> 和</span><span>t</span><span>ij</span><span> ，表示从剧情点</span><span>i</span><span>可以前往剧情点</span><span>b</span><span>ij,</span><span>并且观看这段支线剧情需要花费 </span><span>t</span><span>ij</span><span> 的时间。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>输出一行包含一个整数，表示</span><span>JYY</span><span>看完所有支线剧情所需要的最少时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 </p>
<p>2 4 3 5 4 </p>
<p>2 5 5 6 6 </p>
<p>0 </p>
<p>0 </p>
<p>0 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>24</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N≤300</p>
</div>
</div>