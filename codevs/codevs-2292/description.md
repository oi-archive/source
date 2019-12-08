<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【Shadow 1】第二题</p>
<p>Shadow最近知道了图灵机是什么（Shadow：就是一行格子和一个机器头移来移去的呗！），于是他突发奇想，创造了一个新游戏——“图灵机游戏”（Shadow：好听吧？）。</p>
<p>游戏规则如下：</p>
<p>在一条长长的纸上有N个格子，每个格子上都有一个数，第i格的数记为Ai，机器头刚开始在第1格。这个游戏有两个操作：</p>
<p>1.如果现在在第i格，则可以移动机器头到第Ai格；</p>
<p>2.把某个Ai减少或增加1。</p>
<p>然而，fotile96看了之后却不以为然。“嗯，你挑战一下用最少次数使机器头到达第N格吧，这样好玩些……”</p>
<p>现在，Shadow已经快Crazy了。于是，Shadow把脸转向了你……</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>第1行，1个整数N；</div>
<div>第2行，N个整数Ai。</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>1行，1个整数，为最少的操作次数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>5</div>
<div>3 4 2 5 3</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于30%的数据，1≤N≤10；</span><br><span>对于60%的数据，1≤N≤1000；</span><br><span>对于100%的数据，1≤N≤100000，1≤Ai≤N。</span></p>
&lt;h4&gt;样例解释&lt;/h4&gt;
<div>1.先将第1格的值加1</div>
<div>2.跳到第4格</div>
<div>3.跳到第5格，结束游戏</div>
<p><span><br></span></p>
</div>
</div>