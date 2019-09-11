# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
Contra(李超)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：3.0s   内存限制：512.0MB
</div>
<div id="psrc" style="margin-top:20px;display:block;">
<h3>
【试题来源】
</h3>
<div class="pdcont">
2012集训队互测-李超
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
偶然间，chnlich发现了他小时候玩过的一个游戏“魂斗罗”，于是决定怀旧。但是这是一个奇怪的魂斗罗MOD。<br/>
有N个关卡，初始有Q条命。<br/>
每通过一个关卡，会得到u分和1条命，生命上限为Q。<br/>
其中u=min(最近一次连续通过的关数,R)。<br/>
若没有通过这个关卡，将会失去1条命，并进入下一个关卡。<br/>
当没有生命或没有未挑战过的关卡时，游戏结束，得到的分数为每关得到的分数的总和。<br/>
由于chnlich好久不玩这个游戏了，每条命通过每个关卡的概率均为p(0&lt;=p&lt;=1)，原先chnlich的最高分纪录是S。<br/>
现在chnlich想要知道，当p至少为多少时，chnlich期望获得的总分数能够超过原先的最高分。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入共一行，分别表示整数N，整数R，整数Q，原先的最高分整数S。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出共一行，若不存在这样的p，输出&#34;Impossible.&#34;（不包含引号），否则输出p（保留6位小数）。<br/>
</div>
<h3>
【样例输入一】
</h3>
<div class="pdcont">
4 2 1 5<br/>
</div>
<h3>
【样例输出一】
</h3>
<div class="pdcont">
0.880606<br/>
</div>
<h3>
【样例输入二】
</h3>
<div class="pdcont">
12 3 2 12<br/>
</div>
<h3>
【样例输出二】
</h3>
<div class="pdcont">
0.687201<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于20%的数据，N&lt;=15<br/>
对于50%的数据，N&lt;=10000<br/>
对于100%的数据，N&lt;=10^8,1&lt;=R&lt;=20,1&lt;=Q&lt;=5,保证S是一个可能出现的分数。<br/>
</div>
<h3>
【补充说明】
</h3>
<div class="pdcont">
例如，当N=12，R=3，Q=2时<br/>
第一关：未通过 u=0 获得分数0 总分为0 剩余生命1<br/>
第二关：通过 获得分数1 总分为1 剩余生命2<br/>
第三关：通过 获得分数2 总分为3 剩余生命2<br/>
第四关：通过 获得分数3 总分为6 剩余生命2<br/>
第五关：通过 获得分数3 总分为9 剩余生命2<br/>
第六关：未通过 获得分数0 总分为9 剩余生命1<br/>
第七关：通过 获得分数1 总分为10 剩余生命2<br/>
第八关：未通过 获得分数0 总分为10 剩余生命1<br/>
第九关：未通过 获得分数0 总分为10 剩余生命0<br/>
游戏结束 总分为10<br/>
这是chnlich游戏的一种可能性<br/>
</div>
</div>
