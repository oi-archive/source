# 

 
 # 题目背景 
正在rainbow的城堡游玩的freda恰好看见了在地毯上跳舞卖萌的水叮当……于是……<BR>freda：“呜咕&gt;_&lt;&nbsp;我也要卖萌T_T！” 

 
 # 题目描述 
rainbow给了freda&nbsp;N秒的自由活动时间，不过由于刚刚游览城堡有些累了，freda只想花B秒的时间来卖萌，剩下的时间她要在rainbow的城堡里睡个好觉好好休息一下。<BR>rainbow给这N秒每秒定义了一个值Ui，如果第i秒钟freda在卖萌，那么她可以获得Ui点卖萌指数lala~<BR>freda开始卖萌后可以随时停止，休息一会儿之后再开始。不过每次freda开始卖萌时，都需要1秒来准备=&nbsp;=，这一秒是不能获得卖萌指数的。当然，freda卖萌和准备的总时间不能超过B。<BR>更特殊的是，这N秒钟时间是环形的。也就是freda可以从任意时间开始她的自由活动并持续N秒。<BR>为了使自己表现得比水叮当更萌，现在freda想知道，她最多能获得多少卖萌指数呢？<BR> 

 
 # 输入格式 
第一行包含两个整数N和B。<BR>第2~N+1行每行一个整数，其中第i+1行的整数表示Ui。 

 
 # 输出格式 
输出一个整数，表示freda可以获得的最大卖萌指数。 

 
 # 提示 
对于60%的数据，N&lt;=100<BR>对于100%的数据，0&lt;=B&lt;=N&lt;=3600，0&lt;=Ui&lt;=200000。<BR><BR>样例解释：<BR>freda选择从第2秒开始她的自由活动，持续N秒（2、3、4、5、1）。第4秒开始准备，第5、1秒卖萌（时间是环形的），获得2+4=6点卖萌指数。 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>5 3
2
0
3
1
4
</td><td>6</td></tr></table>
