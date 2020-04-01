
# Description

<div class="content"><p><span style="font-size: medium">正在rainbow的城堡游玩的freda恰好看见了在地毯上跳舞卖萌的水叮当……于是……<br/>
freda：“呜咕&gt;_&lt; 我也要卖萌T_T！”<br/>
rainbow给了freda N秒的自由活动时间，不过由于刚刚游览城堡有些累了，freda只想花B秒的时间来卖萌，剩下的时间她要在rainbow的城堡里睡个好觉好好休息一下。<br/>
rainbow给这N秒每秒定义了一个值Ui，如果第i秒钟freda在卖萌，那么她可以获得Ui点卖萌指数lala~<br/>
freda开始卖萌后可以随时停止，休息一会儿之后再开始。不过每次freda开始卖萌时，都需要1秒来准备= =，这一秒是不能获得卖萌指数的。当然，freda卖萌和准备的总时间不能超过B。<br/>
更特殊的是，这N秒钟时间是环形的。也就是freda可以从任意时间开始她的自由活动并持续N秒。<br/>
为了使自己表现得比水叮当更萌，现在freda想知道，她最多能获得多少卖萌指数呢？<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行包含两个整数N和B。<br/>
第2~N+1行每行一个整数，其中第i+1行的整数表示Ui。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出一个整数，表示freda可以获得的最大卖萌指数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
2<br/>
0<br/>
3<br/>
1<br/>
4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
对于100%的数据，0&lt;=B&lt;=N&lt;=3600，0&lt;=Ui&lt;=200000。<br/>
<br/>
样例解释：<br/>
freda选择从第2秒开始她的自由活动，持续N秒（2、3、4、5、1）。第4秒开始准备，第5、1秒卖萌（时间是环形的），获得2+4=6点卖萌指数。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize6">Poetize6</a></p></div>

