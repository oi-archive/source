# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
航班安排(王钦石)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：1.0s   内存限制：256.0MB
</div>
<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【背景】
</h3>
<div class="pdcont">
1.wqs爱好模拟飞行。<br/>
2.clj开了一家神犇航空，由于clj还要玩游戏，所以公司的事务由你来打理。<br/>
注意：题目中只是用了这样一个背景，并不与真实/模拟飞行相符<br/>
</div>
<h3>
【问题描述】
</h3>
<div class="pdcont">
神犇航空有K架飞机，为了简化问题，我们认为每架飞机都是相同的。神犇航空的世界中有N个机场，以0..N-1编号，其中0号为基地机场，每天0时刻起飞机才可以从该机场起飞，并不晚于T时刻回到该机场。一天，神犇航空接到了M个包机请求，每个请求为在s时刻从a机场起飞，在恰好t时刻到达b机场，可以净获利c。设计一种方案，使得总收益最大。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行，4个正整数N,M,K,T，如题目描述中所述；<br/>
以下N行，每行N个整数，描述一个N*N的矩阵t，t­<sub>i,j</sub>表示从机场i空载飞至机场j，需要时间t<sub>i,j</sub>；<br/>
以下N行, 每行N个整数，描述一个N*N的矩阵f，f­<sub>i,j</sub>表示从机场i空载飞至机场j，需要费用f<sub>i,j</sub>；<br/>
以下M行，每行5个整数描述一个请求，依次为a,b,s,t,c。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
仅一行，一个整数，表示最大收益。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
2 1 1 10<br/>
0 5<br/>
5 0<br/>
0 5<br/>
5 0<br/>
0 1 0 5 10<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
5<br/>
</div>
<h3>
【数据规模及约定】
</h3>
<div class="pdcont">
对于10%的测试数据，K=1；<br/>
另有20%的测试数据，K=2；<br/>
对于全部的测试数据，N,M&lt;=200，K&lt;=10，T&lt;=3000，t<sub>i,j</sub>&lt;=200，f<sub>i,j</sub>&lt;=2000，0&lt;=a,b&lt;N，0&lt;=s&lt;=t&lt;=T，0&lt;=c&lt;=10000，t<sub>i,i</sub>=f<sub>i,i</sub>=0，t<sub>i,j</sub>&lt;=t<sub>i,k</sub>+t<sub>k,j</sub>，f<sub>i,j</sub>&lt;=f<sub>i,k</sub>+f<sub>k,j</sub>。<br/>
</div>
</div>
