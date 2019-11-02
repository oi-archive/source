<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　SJZEZ和TSYZ正在进行一轮足球联谊赛，根据规则，这轮比赛有两场，一场在SJZEZ的主场进行，一场在TSYZ的主场进行。胜负判断标准如下：</span><br><span>　　　　1.在两场比赛中进球总数较多的一方赢得比赛。</span><br><span>　　　　2.如果双方进球总数相同，在对方主场进球更多的一方赢得比赛。</span><br><span>　　　　3.如果1、2都相同，胜利者将会随机产生= =</span><br><span>　　双方已经进行了一场比赛，作为SJZEZ的队长，忘川沧月童鞋想知道：</span><br><span>　　　　(1)第二场sjzez最少需要进多少球，才有可能赢得比赛。</span><br><span>　　　　(2)第二场sjzez进不超过多少个球，tsyz才有可能赢得比赛。</span><br><span>　　已知在一场比赛中，一方的进球数不可能多于30个。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行一个整数t，表示该测试点中数据的组数。<br>　　接下来t行，每行一个字符串，描述该组数据中第一场比赛的情况，形式如下：<br>　　　　wccy's team played where game, scored x goals, and conceded y goals.<br>　　其中where是'home'或者'away'中的一个，home表示第一场比赛是在sjzez的主场进行，away表示第一场比赛是在tsyz的主场进行。<br>　　x，y是整数，分别表示忘川沧月的队伍的进球数，和对方的进球数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>输出t行，每行包含两个用空格隔开的整数，分别是两个问题的答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>wccy's team played home game, scored 28 goals, and conceded 0 goals.<br>wccy's team played home game, scored 1 goals, and conceded 1 goals.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0 1<br>1 29</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　　<span>对于100%的数据，1&lt;=t&lt;=500，0&lt;=x,y&lt;=30.</span></p>
<p><span><br></span></p>
<p><span>来源：Nescafe 23</span></p>
</div>
</div>