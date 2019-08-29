<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　输入三个自然数$$N$$，$$i$$，$$j$$ （$$1\le i\le N$$，$$1\le j\le N$$），输出在一个$$N\times N$$格的棋盘中，与格子$$(i, j)$$同行、同列、同一对角线的所有格子的位置。</div>
# 输入格式

<div class="pdcont">　　输入共三行，分别输入自然数$$N$$，$$i$$，$$j$$。其中保证$$N\le 24$$且$$1\le i\le N$$，$$1\le j\le N$$。</div>
# 输出格式

<div class="pdcont">　　输出共四行。第一行为与格子$$(i, j)$$同行的所有格子的位置，第二行为与格子$$(i, j)$$同列的所有格子的位置，第三行为从左上到右下对角线上的格子的位置，第四行为从左下到右上对角线上的格子的位置。</div>
# 样例输入

<div class="pddata">4<br/>
2<br/>
3</div>
# 样例输出

<div class="pddata">(2,1)(2,2)(2,3)(2,4)<br/>
(1,3)(2,3)(3,3)(4,3)<br/>
(1,2)(2,3)(3,4)<br/>
(4,1)(3,2)(2,3)(1,4)</div>
# 输入输出样例解释

<div class="pdcont">　　$$N=4$$，$$i=2$$，$$j=3$$表示了棋盘中的第二行第三列的格子，如下图：<br/>
<img width="342" height="148" src="source/tsinsen/A1101/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9WVJxcXk3OVQ=.do"/><br/>
<br/>
　　(2,1) (2,2) (2,3) (2,4) 			{同一行上格子的位置}<br/>
　　(1,3) (2,3) (3,3) (4,3)			{同列列上格子的位置}<br/>
　　(1,2) (2,3) (3,4)	         	{左上到右下对角线上的格子的位置}<br/>
　　(4,1) (3,2) (2,3) (1,4)   		{左下到右上对角线上的格子的位置}</div>

</div>