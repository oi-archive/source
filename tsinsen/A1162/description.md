<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定A、B、C三根足够长的细柱，在A柱上放有2<i>n</i>个中间有孔的圆盘，共有<i>n</i>个不同的尺寸，每个尺寸都有两个相同的圆盘，注意这两个圆盘是不加区分的（下图为<i>n</i>=3的情形）。现要将这些圆盘移到C柱上，在移动过程中可放在B柱上暂存。要求：<br/>
　　（1）每次只能移动一个圆盘；<br/>
　　（2）A、B、C三根细柱上的圆盘都要保持上小下大的顺序；<br/>
　　任务：设<i>A<sub>n</sub></i>为2<i>n</i>个圆盘完成上述任务所需的最少移动次数，对于输入的<i>n</i>，输出<i>A<sub>n</sub></i>。<br/>
<img height="214" width="358" src="source/tsinsen/A1162/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9cjg4QjJBZkU=.do"/></div>
# 输入格式

<div class="pdcont">　　一个正整数<i>n</i>，表示在A柱上放有2<i>n</i>个圆盘。</div>
# 输出格式

<div class="pdcont">　　仅一行，包含一个正整数, 为完成上述任务所需的最少移动次数<i>A<sub>n</sub></i>。</div>
# 样例输入

<div class="pddata">1</div>
# 样例输出

<div class="pddata">2</div>
# 样例输入

<div class="pddata">2</div>
# 样例输出

<div class="pddata">6</div>
# 数据规模和约定

<div class="pdcont">　　对于50%的数据，1&lt;=<i>n</i>&lt;=25<br/>
　　对于100%的数据，1&lt;=<i>n</i>&lt;=200</div>
# 提示

<div class="pdcont">　　设法建立<i>A<sub>n</sub></i>与<i>A<sub>n</sub></i><sub>-1</sub>的递推关系式。</div>

</div>