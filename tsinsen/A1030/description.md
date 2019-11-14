<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　计算机系学生会体育部组织了一次“酒井杯”足球联赛，有若干支球队参加，现在联赛已经圆满落幕，各队的积分、净胜球、进球数已经计算出来了，现在要你编写一个程序计算各支球队的排名，然后按照名次从高到低的顺序将各个球队的名字打印出来。<br/>
　　球队的规则如下：<br/>
　　1、先比较积分，积分高者名次在前；<br/>
　　2、如果积分相同则比较净胜球，净胜球多者名次在前；<br/>
　　3、如果积分、净胜球都相同则比较进球数，进球数多者名次在前；<br/>
　　4、对于积分、净胜球和进球数都一样的球队，根据他们的名称按照字典顺序排列。<br/>
　　现在假设各个球队的名称都是由大写英文字母组成，并且没有重名的球队。</div>
# 输入格式

<div class="pdcont">　　第一行是一个正整数N(2&lt;=N&lt;=10)，代表球队的数目<br/>
　　接下来有N行，每一行均包括一个字符串和3个整数，其中字符串代表球队的名称，长度在2与20之间，3个整数依次为球队的积分，净胜球和进球数，其中积分和进球数是0到100间的整数，净胜球的绝对值小于100。</div>
# 输出格式

<div class="pdcont">　　共N行，每行输出一个字符串，即球队的名称。</div>
# 样例输入

<pre class="pddata">4
ACMILAN 5 1 5
SCHALKE 5 1 7
FENERBAHCE 4 -1 7
PSV 7 -1 2
</pre>
<p></p>
<br/><p></p><p class="subtitle">样例输出</p><p class="probcontent">
</p><p><font face="Times New Roman" size="3"></font></p><pre><font face="Times New Roman" size="3">PSV
SCHALKE
ACMILAN
FENERBAHCE
</font></pre>
<p></p>
<br/>



</div>