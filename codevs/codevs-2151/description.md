<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了能在下一次跑步比赛中有好的发挥，贝茜在一条山路上开始了她的训练<br>。贝茜希望能在每次训练中跑得尽可能远，不过她也知道农场中的一条规定：<br>奶牛独自进山的时间不得超过M秒(1 &lt;= M &lt;= 10,000,000)。</p>
<p>整条山路被贝茜划分成T个长度相同的小段(1 &lt;= T &lt;= 100,000)，并且，<br>贝茜用S_i表示第i个小段的路况。S_i为u，f，d这3个字母之一，它们分别表示<br>第i个小段是上坡、平地，或是下坡。</p>
<p>贝茜要花U秒(1 &lt;= U &lt;= 100)才能跑完一段上坡路，跑完一段平地的耗时是<br>F秒(1 &lt;= F &lt;= 100)，跑完一段下坡路要花D秒(1 &lt;= D &lt;= 100)。注意，沿山路<br>原路返回的时候，原本是上坡路的路段变成了下坡路，原本是下坡路的路段变成<br>了上坡路。</p>
<p>贝茜想知道，在能按时返回农场的前提下，她最多能在这条山路上跑多远。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入格式:</p>
<p>* 第1行: 5个用空格隔开的整数：M，T，U，F，以及D</p>
<p>* 第2..T+1行: 第i+1行为1个字母S_i，描述了第i段山路的路况</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出格式:</p>
<p>* 第1行: 输出1个整数，为贝茜在按时回到农场的前提下，最多能跑到多远</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>13 5 3 2 1<br>u<br>f<br>u<br>d<br>f</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>各个测试点1秒</p>
</div>
</div>