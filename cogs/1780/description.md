# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
矩阵乘法（梁 盾）
</div>
<div style="text-align:center;font-size:14px;vertical-align:middle;" id="pres">
<div style="font-weight:bold;margin:8px 0px 6px;">
时间限制：<span style="text-decoration:underline;">2.0s</span>   内存限制：<span style="text-decoration:underline;">256.0MB</span> 
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
给你一个N*N的矩阵，不用算矩阵乘法，但是每次询问一个子矩形的第K小数。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行两个数N,Q，表示矩阵大小和询问组数；<br/>
接下来N行N列一共N*N个数，表示这个矩阵；<br/>
再接下来Q行每行5个数描述一个询问：x1,y1,x2,y2,k表示找到以(x1,y1)为左上角、以(x2,y2)为右下角的子矩形中的第K小数。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每组询问输出第K小的数。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
2 2<br/>
2 1<br/>
3 4<br/>
1 2 1 2 1<br/>
1 1 2 2 3<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1<br/>
3<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
矩阵中数字是10<sup>9</sup>以内的非负整数；<br/>
20%的数据：N&lt;=100,Q&lt;=1000；<br/>
40%的数据：N&lt;=300,Q&lt;=10000；<br/>
60%的数据：N&lt;=400,Q&lt;=30000；<br/>
100%的数据：N&lt;=500,Q&lt;=60000。<br/>
</div>
</div>
