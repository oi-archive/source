# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
特技飞行(王钦石)
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
神犇航空开展了一项载客特技飞行业务。每次飞行长N个单位时间，每个单位时间可以进行一项特技动作，可选的动作有K种，每种动作有一个刺激程度Ci。如果连续进行相同的动作，乘客会感到厌倦，所以定义某次动作的价值为(距上次该动作的时间)*Ci，若为第一次进行该动作，价值为0。安排一种方案，使得总价值最大。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行，两个数，N和K，如上所述；<br/>
第二行，K个正整数，表示K种动作的Ci值。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
仅一行，一个整数，表示最大总价值。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5 2<br/>
2 2<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
12<br/>
</div>
<h3>
【数据规模及约定】
</h3>
<div class="pdcont">
对于10%的测试数据，N&lt;=20，K&lt;=3<br/>
对于全部的测试数据，1&lt;=N&lt;=1000，1&lt;=K&lt;=300，0&lt;=Ci&lt;=1000。<br/>
</div>
</div>
