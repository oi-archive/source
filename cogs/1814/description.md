# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
黑白染色(钟沛林)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：2.0s   内存限制：256.0M
</div>
<div id="pcont" style="margin-top:20px;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
你有一个n*m的矩形，一开始所有格子都是白色，然后给出一个目标状态的矩形，有的地方是白色，有的地方是黑色，你每次可以选择一个连通块（四连通块，且不要求颜色一样）进行染色操作（染成白色或者黑色）。问最少操作次数。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行两个数n，m表示矩形大小。<br/>
接下来n行描述目标状态，每行m个字符，’W’表示白色，’B’表示黑色。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
一行一个整数表示操作数。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 3<br/>
WBW<br/>
BWB<br/>
WBW<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
2<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
100%的数据n&lt;=50,m&lt;=50<br/>
15%的数据n*m&lt;=15<br/>
另外15%的数据m=1<br/>
</div>
</div>
