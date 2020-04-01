<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont">　　单选错位</div>
# 问题描述

<div class="pdcont">　　gx和lc去参加noip初赛，其中有一种题型叫单项选择题，顾名思义，只有一个选项是正确答案。试卷上共有<i>n</i>道单选题，第<i>i</i>道单选题有<i>a<sub>i</sub></i>个选项，这<i>a<sub>i</sub></i>个选项编号是1,2,3,…,<i>a<sub>i</sub></i>，每个选项成为正确答案的概率都是相等的。lc采取的策略是每道题目随机写上1-<i>a<sub>i</sub></i>的某个数作为答案选项，他用不了多少时间就能期望做对<img width="40" height="59" src="source/tsinsen/A1225/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9aE5RSHI1TjI=.do"/>道题目。gx则是认认真真地做完了这<i>n</i>道题目，可是等他做完的时候时间也所剩无几了，于是他匆忙地把答案抄到答题纸上，没想到抄错位了：第<i>i</i>道题目的答案抄到了答题纸上的第<i>i</i>+1道题目的位置上，特别地，第<i>n</i>道题目的答案抄到了第1道题目的位置上。现在gx已经走出考场没法改了，不过他还是想知道自己期望能做对几道题目，这样他就知道会不会被lc鄙视了。<br/>
　　我们假设gx没有做错任何题目，只是答案抄错位置了。</div>
# 输入格式

<div class="pdcont">　　<i>  n</i>很大，为了避免读入耗时太多，输入文件只有5个整数参数<i>n</i>, <i>A</i>, <i>B</i>, <i>C</i>, <i>a</i><sub>1</sub>，由上交的程序产生数列<i>a</i>。下面给出pascal/C/C++的读入语句和产生序列的语句（默认从标准输入读入）：<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">// for pascal<br/>
readln(n,A,B,C,q[1]);<br/>
for i:=2 to n do<br/>
q[i] := (int64(q[i-1]) * A + B) mod 100000001;<br/>
for i:=1 to n do<br/>
q[i] := q[i] mod C + 1;<br/>
<br/>
</td></tr></tbody></table><br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">// for C/C++<br/>
scanf(&#34;%d%d%d%d%d&#34;,&amp;n,&amp;A,&amp;B,&amp;C,a+1);<br/>
for (int i=2;i&lt;=n;i++)<br/>
a[i] = ((long long)a[i-1] * A + B) % 100000001;<br/>
for (int i=1;i&lt;=n;i++)<br/>
a[i] = a[i] % C + 1;<br/>
<br/>
</td></tr></tbody></table><br/>
　　选手可以通过以上的程序语句得到<i>n</i>和数列<i>a</i>（<i>a</i>的元素类型是32位整数），<i>n</i>和<i>a</i>的含义见题目描述。</div>
# 输出格式

<div class="pdcont">　　输出一个实数，表示gx期望做对的题目个数，保留三位小数。</div>
# 样例输入

<div class="pddata">3 2 0 4 1</div>
# 样例输出

<div class="pddata">1.167</div>
# 样例说明

<div class="pdcont">　　a[] = {2,3,1}<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">正确答案<br/>
</td><td style="border:solid 1.0pt">gx的答案<br/>
</td><td style="border:solid 1.0pt">做对题目<br/>
</td><td style="border:solid 1.0pt">出现概率<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">{1,1,1}<br/>
</td><td style="border:solid 1.0pt">{1,1,1}<br/>
</td><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt">1/6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">{1,2,1}<br/>
</td><td style="border:solid 1.0pt">{1,1,2}<br/>
</td><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">1/6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">{1,3,1}<br/>
</td><td style="border:solid 1.0pt">{1,1,3}<br/>
</td><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">1/6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">{2,1,1}<br/>
</td><td style="border:solid 1.0pt">{1,2,1}<br/>
</td><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">1/6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">{2,2,1}<br/>
</td><td style="border:solid 1.0pt">{1,2,2}<br/>
</td><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt">1/6<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">{2,3,1}<br/>
</td><td style="border:solid 1.0pt">{1,2,3}<br/>
</td><td style="border:solid 1.0pt">0<br/>
</td><td style="border:solid 1.0pt">1/6<br/>
</td></tr></tbody></table><br/>
　　共有6种情况，每种情况出现的概率是1/6，gx期望做对(3+1+1+1+1+0)/6 = 7/6题。（相比之下，lc随机就能期望做对11/6题）</div>
# 数据规模和约定

<div class="pdcont">　　对于30%的数据 n≤10, C≤10<br/>
　　对于80%的数据 n≤10000, C≤10<br/>
　　对于90%的数据 n≤500000, C≤100000000<br/>
　　对于100%的数据 2≤n≤10000000, 0≤A,B,C,<i>a</i><sub>1</sub>≤100000000</div>

</div>