<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　设有有$$2^n$$（$$n\le 6$$）个球队进行单循环比赛，计划在$$2^n-1$$天内完成，每个队每天进行一场比赛。设计一个比赛的安排，使在$$2^n-1$$天内每个队都与不同的对手比赛。<br/>
　　例如$$n=2$$时的比赛安排：<br/>
　　队    1  2                3  4<br/>
　　比赛  1==2               3==4                   一天<br/>
　　1==3               2==4                二天<br/>
　　1==4           2==3             三天</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含以个整数$$n$$。</div>
# 输出格式

<div class="pdcont">　　输出$$2^n-1$$行，每行开头为一对尖括号，里面输出天数序号。随后写出这天的安排。详细格式见样例。有多个方案则输出字典序最小的方案。</div>
# 样例输入

<div class="pddata">2</div>
# 样例输出

<div class="pddata">&lt;1&gt;1-2,3-4<br/>
&lt;2&gt;1-3,2-4<br/>
&lt;3&gt;1-4,2-3</div>
# 数据规模和约定

<div class="pdcont">　　$$n\le 6$$</div>

</div>