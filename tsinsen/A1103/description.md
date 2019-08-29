<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　设有$$2^n$$ $$(n\le 6)$$个球队进行单循环比赛，计划在$$2^n-1$$天内完成，每个队每天进行一场比赛。设计一个比赛的安排，使在$$2^n-1$$天内每个队都与不同的对手比赛。</div>
# 输入格式

<div class="pdcont">　　输入共一行，输入$$n$$的数值。</div>
# 输出格式

<div class="pdcont">　　输出共$$2^n-1$$行，第$$i$$行输出第$$i$$天的比赛安排。<br/>
　　格式为：&lt;$$i$$&gt;A-B C-D ……。其中$$i$$是天数，A，B分别为比赛双方的编号，每行共$$2^{n-1}$$个比赛场次。</div>
# 样例输入

<div class="pddata">2</div>
# 样例输出

<div class="pddata">&lt;1&gt;1-2 3-4<br/>
&lt;2&gt;1-3 2-4<br/>
&lt;3&gt;1-4 2-3</div>
# 数据规模和约定

<div class="pdcont">　　$$1\le n\le 4$$</div>

</div>