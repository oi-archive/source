# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
串（梁 盾）
</div>
<div style="text-align:center;font-size:14px;vertical-align:middle;" id="pres">
<div style="font-weight:bold;margin:8px 0px 6px;">
时间限制：<span style="text-decoration:underline;">1.0s</span>   内存限制：<span style="text-decoration:underline;">256.0MB</span> 
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
给你一个串s[0~n-1],要求你选择两个数i,j，满足0&lt;=i&lt;=j&lt;=n，然后将s[0~i-1]、s[i~j-1]、s[j~n-1]翻转，要求翻转后的串字典序最小。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
本题有多组数据，第一行一个数T，表示数据组数。<br/>
每组数据占一行，为一个串。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每组数据输出两个数i、j，即变化后字典序最小的方案，多种方案任意输出一组方案即可。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
2<br/>
bacbadcba<br/>
abc<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
2 5<br/>
1 2<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
串由小写字母构成；<br/>
令S为所有串长度之和；<br/>
对于10%的数据，S&lt;=300；<br/>
对于30%的数据，S&lt;=2000；<br/>
对于60%的数据，S&lt;=200000；<br/>
对于100%的数据，S&lt;=10000000；<br/>
请使用gets或者scanf或者更快的方法读入；<br/>
数据有梯度。<br/>
</div>
</div>
