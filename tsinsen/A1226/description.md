<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　为了提高自己的实力，gx想要制定一个合理的刷题计划。这里我们用实数来表示题目的难度，并且把刷题计划中由题目难度组成的序列称为刷题序列。gx刷题最喜欢循序渐进的方式，最理想的情况莫过于刷题序列是个等差数列了。但是这很难做到，于是我们定义一个刷题序列<i>a</i>的偏离值 <img width="175" height="50" src="source/tsinsen/A1226/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ODJMdEFiNTI=.do"/>，其中<i>L</i>是给定的一个常数。<br/>
　　现在gx的老师已经布置给了他<i>n</i>道必做题，同时他还有空余时间从OJ上找<i>m</i>道题目来刷。他不希望改变这<i>n</i>道必做题的相对顺序，但是选做题的难度以及在数列中的位置都是任意的（OJ上的题目太多了，随你怎么挑）。<br/>
　　gx希望你帮他设计一个刷题序列，使得该序列的偏离值最小。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含三个数：<i>n</i>, <i>m</i>, <i>L</i>。<i>n</i>是整数，表示必做题有<i>n</i>道，<i>m</i>是整数，表示选做题有<i>m</i>道，<i>L</i>是实数。第二行包含<i>n</i>个实数，依次表示每道必做题的难度。</div>
# 输出格式

<div class="pdcont">　　输出一个实数，表示最小的偏离值。保留三位小数。</div>
# 样例输入

<div class="pddata">4 3 1.0<br/>
1 4 5 3</div>
# 样例输出

<div class="pddata">8.000</div>
# 样例说明

<div class="pdcont">　　将原序列(1,4,5,3)变成(1,2,3,4,5,4,3)，偏离值为8.00。</div>
# 数据规模和约定

<div class="pdcont">　　对于30%的数据 n≤500, m≤200<br/>
　　对于70%的数据 n≤20000, m≤100000<br/>
　　对于100%的数据 1≤n≤50000, 1≤m≤100000000, -100≤L≤100, |<i>a</i><sub>i</sub>|≤100<br/>
　　均匀分布着50%的数据 L=0</div>

</div>