<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　一个平面直角坐标系上，有N个点，标号为1到N，其中第i个点的坐标为(x[i], y[i])。<br/>
　　求满足以下两个条件的点列{p[i]}的数目（假设{p[i]}的长度为M）：<br/>
　　1) 对任意1 &lt;= i &lt; j &lt;= M，必有y[p[i]] &gt; y[p[j]]；<br/>
　　2) 对任意3 &lt;= i &lt;= M，必有x[p[i-1]] &lt; x[p[i]] &lt; x[p[i-2]]或者x[p[i-2]] &lt; x[p[i]] &lt; x[p[i-1]]。<br/>
　　求满足条件的非空序列{p[i]}的数目，结果对一个整数Q取模。</div>
# 输入格式

<div class="pdcont">　　第1行是两个由空格隔开的整数：N和Q。<br/>
　　第2行到第N+1行，每行有两个整数。其中的第i行的两个整数分别是x[i]和y[i]。</div>
# 输出格式

<div class="pdcont">　　输出文件只有一行，包含一个整数，表示序列{p[i]}的数目对Q取模的结果。</div>
# 样例输入

<div class="pddata">4 100<br/>
2 2<br/>
3 1<br/>
1 4<br/>
4 3</div>
# 样例输出

<div class="pddata">14</div>
# 样例说明

<div class="pdcont">　　一共4个点，位置如下：<br/>
<img width="94" height="78" src="source/tsinsen/A1210/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Ujc2QkhCZ0o=.do"/><br/>
<br/>
　　如果M=4, 那么只有1种序列符合要求,如下图所示：<br/>
<br/>
<img width="93" height="80" src="source/tsinsen/A1210/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NHRqOHlHN24=.do"/><br/>
　　如果M = 3，那么有3种序列符合要求，如下图：<br/>
<br/>
<img width="322" height="81" src="source/tsinsen/A1210/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NWFGTWdyZ0w=.do"/><br/>
　　如果M = 2，那么有6种序列符合要求，如下图：<br/>
<img width="325" height="174" src="source/tsinsen/A1210/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TkozQTNmSGU=.do"/><br/>
<br/>
<br/>
<br/>
　　如果M = 1，也就是点列只包含一个点的情况。那么有4种序列。明显都符合要求。<br/>
　　所以一共就有1 + 3 + 6 + 4一共14种序列符合要求。</div>
# 数据规模和约定

<div class="pdcont">　　对于25%的数据，N &lt;= 50；对于40%的数据，N &lt;= 700；对于60%的数据，N &lt;= 2000；对于70%的数据，N &lt;= 4000；对于100%的数据，1 &lt;= N &lt;= 7000。<br/>
　　对于100%的数据，有1 &lt;= Q &lt;= 1000000000。<br/>
　　对于50%的数据，保证对任何的i，x[i]和y[i]是1到N之间的整数；对于100%的数据，保证对任何的i，x[i]和y[i]都是1到2000000000之间的整数。<br/>
　　对于100%的数据，保证有当i != j时，有x[i] != x[j]且y[i] != y[j]。</div>

</div>