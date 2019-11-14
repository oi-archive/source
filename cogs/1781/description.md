# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
最远点（梁 盾）
</div>
<div style="text-align:center;font-size:14px;vertical-align:middle;" id="pres">
<div style="font-weight:bold;margin:8px 0px 6px;">
时间限制：0.5<span style="text-decoration:underline;">s</span>   内存限制：<span style="text-decoration:underline;">256.0MB</span> 
</div>
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
【问题描述】
</h3>
<div class="pdcont">
给你一个N个点的凸多边形，求离每一个点最远的点。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
本题有多组数据，第一行一个数T，表示数据组数。<br/>
每组数据第一行一个数N，表示凸多边形点的个数，接下来N对数，依次表示1~N这N个点的坐标，按照逆时针给出。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每组数据输出N个数，第i个数表示离第i个点最远的点的编号，如果有多个最远点，输出编号最小的。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
1<br/>
4<br/>
0 0<br/>
1 0<br/>
1 1<br/>
0 1<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
3<br/>
4<br/>
1<br/>
2<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
坐标的绝对值在1e9以内；<br/>
任意点对距离数值的平方不会超过long long；<br/>
令S为每组数据凸多边形点数之和；<br/>
对于20%的数据，S&lt;=2000；<br/>
对于50%的数据，S&lt;=50000；<br/>
对于100%的数据，S&lt;=500000；<br/>
数据有梯度。<br/>
</div>
</div>
