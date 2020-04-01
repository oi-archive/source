<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　A城市有一个巨大的圆形广场，为了绿化环境和净化空气，市政府决定沿圆形广场外圈种一圈树。园林部门得到指令后，初步规划出n个种树的位置，顺时针编号1到n。并且每个位置都有一个美观度Ai，如果在这里种树就可以得到这Ai的美观度。但由于A城市土壤肥力欠佳，两棵树决不能种在相邻的位置（i号位置和i+1号位置叫相邻位置。值得注意的是1号和n号也算相邻位置！）。<br/>
　　最终市政府给园林部门提供了m棵树苗并要求全部种上，请你帮忙设计种树方案使得美观度总和最大。如果无法将m棵树苗全部种上，给出无解信息。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个正整数n、m。<br/>
　　第二行n个整数Ai。</div>
# 输出格式

<div class="pdcont">　　输出一个整数，表示最佳植树方案可以得到的美观度。如果无解输出“Error!”，不包含引号。</div>
# 样例输入

<div class="pddata">7 3<br/>
1 2 3 4 5 6 7</div>
# 样例输出

<div class="pddata">15</div>
# 样例输入

<div class="pddata">7 4<br/>
1 2 3 4 5 6 7</div>
# 样例输出

<div class="pddata">Error!</div>
# 数据规模和约定

<div class="pdcont">　　对于全部数据：m&lt;=n；<br/>
　　-1000&lt;=Ai&lt;=1000<br/>
　　N的大小对于不同数据有所不同：<br/>
<img width="284" height="181" src="source/tsinsen/A1249/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RkxuVDJyTjQ=.do"/></div>

</div>