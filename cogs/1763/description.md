# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
middle(陈立杰)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：3.0s   内存限制：1.0GB
</div>
<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<div class="pdcont">
<h3>
【大意】
</h3>
一个长度为n的序列a，设其排过序之后为b，其中位数定义为b[n/2]，其中a,b从0开始标号,除法取下整。<br/>
给你一个长度为n的序列s。<br/>
回答Q个这样的询问：s的左端点在[a,b]之间,右端点在[c,d]之间的子序列中，最大的中位数。<br/>
其中a&lt;b&lt;c&lt;d。<br/>
位置也从0开始标号。<br/>
我会使用一些方式强制你在线。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行序列长度n。<br/>
接下来n行按顺序给出a中的数。<br/>
接下来一行Q。<br/>
然后Q行每行a,b,c,d，我们令上个询问的答案是x(如果这是第一个询问则x=0)。<br/>
令数组q={(a+x)%n,(b+x)%n,(c+x)%n,(d+x)%n}。<br/>
将q从小到大排序之后，令真正的要询问的a=q[0],b=q[1],c=q[2],d=q[3]。<br/>
输入保证满足条件。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
Q行依次给出询问的答案。<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
0:n,Q&lt;=100<br/>
1,...,5:n&lt;=2000<br/>
0,...,19:n&lt;=20000,Q&lt;=25000<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5<br/>
170337785<br/>
271451044<br/>
22430280<br/>
969056313<br/>
206452321<br/>
3<br/>
3 1 0 2<br/>
2 3 1 4<br/>
3 1 4 0<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
271451044<br/>
271451044<br/>
969056313<br/>
</div>
</div>
