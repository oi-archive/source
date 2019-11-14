<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>"今天你要去远行，送你风雨中….."，伴着凄美的歌声，郭靖夫妇终于踏上征程。为了尽快到达边疆为国效力，他们搭上了2002次列车。可在途径sweet station时，被该站站长缠住了身，是什么原因呢？ <br>　　因为该车站由于经营不善，面临破产，该站负责人早闻黄蓉聪明过人，一定要她帮忙出出主意，挽救车站。 <br>　　该车站有n个车道，由于车道的长度有限，每个车道在某一时刻最多只能停靠一列火车。该站每天将有m列火车从车站经过，其中第i列火车到达车站的时间为Reach[i]，火车上装有价值Cost[i]的货物。 <br>　　如果该火车进站，则车站将获得Cost[i]的1%收益，但由于货物的搬运时间，该火车将在车站停留一段时间Stay[i]，这段时间内，火车将占用车站中的某一个车道。当然，火车也可以不在站中停靠而直接出站，但这样车站将得不到一分钱。 <br>　　要挽救车站，就是要对车站的列车进行调度，使获得的效益最大。当然，解决这个问题对于黄蓉来说并不难，但边疆吃紧，时间不等人，你能帮帮黄蓉，让她脱身吗？ <br>任务:运行你的程序得到该站的最大效益。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行中为两个正整数：n（n≤20）m（m≤100），第2行到第m+1行，每行有3个不超过1000正整数。第i+1行的3个数分别为：Reach[i]， Cost[i]和Stay[i]，它们用单个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅有一行，为车站的最大收益（精确到小数点后2位）。注意，如果火车a从第i车道离开时，火车b刚好到站（即Reach[a]+Stay[a] =Reach[b]），则它不能进入第i车道。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>1 3<br>2 5 1<br>3 4 1<br>5 6 2</span></p>
<div><span style="font-family: Simsun;"><span style="font-family: monospace;"><br></span></span></div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.11</p>

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