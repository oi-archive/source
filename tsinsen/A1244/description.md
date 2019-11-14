<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　lqp在为出题而烦恼，他完全没有头绪，好烦啊…<br/>
　　他首先想到了整数拆分。整数拆分是个很有趣的问题。给你一个正整数N，对于N的一个整数拆分就是满足任意<b><i>m&gt;0</i></b><b><i>，a<sub>1 </sub>,a<sub>2 </sub>,a<sub>3</sub>…a<sub>m</sub>&gt;0</i></b>，且<b><i>a<sub>1</sub>+a<sub>2</sub>+a<sub>3</sub>+…+a<sub>m</sub>=N</i></b>的一个有序集合。通过长时间的研究我们发现了计算对于N的整数拆分的总数有一个很简单的递推式，但是因为这个递推式实在太简单了，如果出这样的题目，大家会对比赛毫无兴趣的。<br/>
　　然后lqp又想到了斐波那契数。定义<b><i>F<sub>0</sub>=0</i></b><b><i>，F<sub>1</sub>=1</i></b><b><i>，F<sub>n</sub>=F<sub>n-1</sub>+F<sub>n-2 </sub>(n&gt;1)</i></b>，F<sub>n</sub>就是斐波那契数的第n项。但是求出第n项斐波那契数似乎也不怎么困难…<br/>
　　lqp为了增加选手们比赛的欲望，于是绞尽脑汁，想出了一个有趣的整数拆分，我们暂且叫它：整数的lqp拆分。和一般的整数拆分一样，整数的lqp拆分是满足任意<b><i>m&gt;0</i></b><b><i>，a<sub>1 </sub>,a<sub>2 </sub>,a<sub>3</sub>…a<sub>m</sub>&gt;0</i></b>，且<b><i>a<sub>1</sub>+a<sub>2</sub>+a<sub>3</sub>+…+a<sub>m</sub>=N</i></b>的一个有序集合。但是整数的lqp拆分要求的不是拆分总数，相对更加困难一些。对于每个拆分，lqp定义这个拆分的权值<b><i>F<sub>a1</sub>F<sub>a2</sub>…F<sub>am</sub></i></b>，他想知道对于所有的拆分，他们的权值之和是多少？简单来说，就是求<br/>
<br/>
<img width="275" height="170" src="source/tsinsen/A1244/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OEdkRjhuZzc=.do"/><br/>
<br/>
<br/>
<br/>
<br/>
　　由于这个数会十分大，lqp稍稍简化了一下题目，只要输出对于N的整数lqp拆分的权值和mod 10<sup>9</sup>+7输出即可。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个整数N。</div>
# 输出格式

<div class="pdcont">　　输出一个整数，为对于N的整数lqp拆分的权值和mod 10<sup>9</sup>+7。</div>
# 样例输入

<div class="pddata">3</div>
# 样例输出

<div class="pddata">5</div>
# 样例说明

<div class="pdcont"><b><i>F<sub>0</sub>=0</i></b><b><i>，F<sub>1</sub>=1</i></b><b><i>，F<sub>2</sub>=1</i></b><b><i>，F<sub>3</sub>=2</i></b><b><i>。</i></b><br/>
　　对于N=3，有这样几种lqp拆分：<br/>
　　3=1+1+1, 权值是1*1*1=1。<br/>
　　3=1+2，权值是1*2=2。<br/>
　　3=2+1，权值是2*1=2。<br/>
　　所以答案是1*1*1+1*2+2*1=5。</div>
# 数据说明

<div class="pdcont">　　20%数据满足：1≤N≤25<br/>
　　50%数据满足：1≤N≤1000<br/>
　　100%数据满足：1≤N≤1000000</div>

</div>