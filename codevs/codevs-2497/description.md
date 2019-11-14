<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　正在rainbow的城堡游玩的freda恰好看见了在地毯上跳舞卖萌的水叮当……于是……</span><br><span>　　freda：“呜咕&gt;_&lt; 我也要卖萌T_T！”</span></p>
<p><span><span>　　rainbow给了freda N秒的自由活动时间，不过由于刚刚游览城堡有些累了，freda只想花B秒的时间来卖萌，剩下的时间她要在rainbow的城堡里睡个好觉好好休息一下。</span><br><span>　　rainbow给这N秒每秒定义了一个值Ui，如果第i秒钟freda在卖萌，那么她可以获得Ui点卖萌指数lala~</span><br><span>　　freda开始卖萌后可以随时停止，休息一会儿之后再开始。不过每次freda开始卖萌时，都需要1秒来准备= =，这一秒是不能获得卖萌指数的。当然，freda卖萌和准备的总时间不能超过B。</span><br><span>　　更特殊的是，这N秒钟时间是环形的。也就是freda可以从任意时间开始她的自由活动并持续N秒。</span><br><span>　　为了使自己表现得比水叮当更萌，现在freda想知道，她最多能获得多少卖萌指数呢？</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行包含两个整数N和B。</span><br><span>　　第2~N+1行每行一个整数，其中第i+1行的整数表示Ui。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>输出一个整数，表示freda可以获得的最大卖萌指数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3<br>2<br>0<br>3<br>1<br>4</p>

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
<p><span>　　对于60%的数据，N&lt;=100</span><br><span>　　对于100%的数据，0&lt;=B&lt;=N&lt;=3600，0&lt;=Ui&lt;=200000。</span><br><br><span>样例解释：</span><br><span>　　freda选择从第2秒开始她的自由活动，持续N秒（2、3、4、5、1）。第4秒开始准备，第5、1秒卖萌（时间是环形的），获得2+4=6点卖萌指数。</span></p>
<p><span><br></span></p>
<p><span>来源：Nescafe 22</span></p>
</div>
</div>