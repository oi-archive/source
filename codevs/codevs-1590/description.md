<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>中国邀请韩国，日本围棋队来参加三国围棋对抗赛，韩国，日本应邀各派了5位超一流高手来参赛，中国围棋队希望能赢得这场比赛，但是这10位高手实力不俗。不过中国队作为东道主，可以在对方选手安排好出场顺序后再决定队员的组成以及出场顺序，以得到最大的获胜概率。</p>
<p>比赛规则如下：先抽签决定第1轮轮空的队，由不轮空的2支队的1号队员进行比赛，失利的队员被淘汰，以后每次由前一轮获胜的队员与前一轮轮空的队剩下的队员中序号最小的队员进行比赛，直到只剩下一个国家的队员为止，这个国家就获得了比赛的胜利。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为一个数n（5&lt;=n&lt;=15），中国队的候选人数。</p>
<p>接下来是n行，每行有10个数</p>
<p>第I+1行的10个数依次表示第I位中国选手对韩国1~5号，日本1~5号的胜率，胜率k（0&lt;=k&lt;=1）。</p>
<p>再接下来是5行，每行有5个数</p>
<p>第I+n+1行的第j个数表示韩国I号选手对日本j号选手的胜率。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅1行，为中国队的最大的获胜概率，保留6位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10<br>0.100 0.260 0.539 0.118 0.333 0.890 0.069 0.181 0.823 0.611 <br>0.428 0.337 0.026 0.090 0.718 0.889 0.616 0.234 0.571 0.440 <br>0.329 0.475 0.280 0.565 0.173 0.161 0.258 0.801 0.288 0.274 <br>0.373 0.222 0.753 0.249 0.835 0.445 0.597 0.152 0.218 0.668 <br>0.164 0.736 0.868 0.757 0.513 0.401 0.610 0.723 0.071 0.015 <br>0.362 0.460 0.682 0.667 0.733 0.224 0.290 0.362 0.532 0.788 <br>0.171 0.400 0.442 0.602 0.800 0.869 0.030 0.128 0.305 0.048 <br>0.791 0.349 0.660 0.129 0.239 0.653 0.008 0.268 0.123 0.660 <br>0.126 0.543 0.704 0.828 0.658 0.078 0.117 0.560 0.587 0.759 <br>0.037 0.804 0.637 0.239 0.188 0.409 0.491 0.540 0.475 0.889 <br>0.329 0.179 0.047 0.325 0.876 <br>0.079 0.865 0.336 0.253 0.058 <br>0.553 0.545 0.088 0.992 0.012 <br>0.792 0.038 0.209 0.829 0.472 <br>0.188 0.399 0.509 0.162 0.347</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.646494</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>搜索+动态规划 有一点难度</p>
</div>
</div>