<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: inherit; font-weight: inherit;"><span style="font-family: inherit; font-weight: inherit;"><img height="183" src="/source/codevs/codevs-3558/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNTU4L2h0dHA6Ly9tZXNzaXN4aC13b3JkcHJlc3Muc3Rvci5zaW5hYXBwLmNvbS91cGxvYWRzLzIwMTQvMTIvMS0zMDB4MTgzLnBuZw==.png" style="" title="1" width="300"></span></p><p style="font-family: inherit; font-weight: inherit;"><span style="font-family: inherit; font-weight: inherit;">每当魔法炮闲暇之时，他总是喜欢玩一些网游来消遣，其中QQ飞车就是一个很好的选择。魔法炮是一个追求速度的人，总是希望自己的车速能够无限增加。于是，他研究了一条名叫“极速飞车”的赛道。这条赛道只有直道没有弯道，所以不会有任何速度损失。所有赛道中有n个特殊的加速带，这些加速带只能使用氮气来触发，而且仅当完整地经过某一条时，你的车速会增加L·v，L为加速带长度。重叠的多条加速带互不影响，效果叠加。也就是说，对于每条加速带，你只能选择加速或不加速。玩家的氮气是无限的，但是只能在加速带上使用。不过由于这条赛道的路面很脆弱，赛道的任何位置最多能承受k个加速叠加，否则就不能通过了。（加速带的起点和终点不计入叠加）魔法炮自然想做赛道之王，所以他想在赛前布置好加速的策略，使他最终的速度最大，因为这条赛道是按到达终点时的速度来排名的。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行四个整数n,k,v0,v.其中v0表示比赛开始的速度.接下来n行每行两个正整数li,ri，表示第i个加速带的起点和终点.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，代表最终的速度.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2 100 50 </p><p>1 3 </p><p>5 6</p><p>3 9</p><p>7 11</p><p>8 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>750</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1&lt;=n&lt;=1000</span></p><p style=""><span style="">1&lt;=li&lt;ri&lt;=10</span><sup>6</sup></p><p><span style="">保证结果不会超过</span><span style="font-family: 'Times New Roman';">int</span><span style="">范围</span></p><p><span style=""></span></p><p><span style="">初始速度</span><span style="">100</span><span style="">，经前四条加速带加速，速度达到</span><span style="">100+(2+1+6+4)*50=750</span><span style="">。但是无法使用第五条加速带，因为</span><span style="">8</span><span style="">和</span><span style="">9</span><span style="">之间已经叠加了</span><span style="">2</span><span style="">次加速。</span></p><p><span style=""></span><br></p><p><br></p>
</div>
</div>