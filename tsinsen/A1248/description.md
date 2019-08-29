<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　lanzerb的部落在A国的上部，他们不满天寒地冻的环境，于是准备向A国的下部征战来获得更大的领土。<br/>
　　A国是一个M*N的矩阵，其中某些地方是城镇，某些地方是高山深涧无人居住。lanzerb把自己的部落分成若干支军队，他们约定：<br/>
　　1.	每支军队可以从任意一个城镇出发，并只能从上往向下征战，不能回头。途中只能经过城镇，不能经过高山深涧。<br/>
　　2.	如果某个城镇被某支军队到过，则其他军队不能再去那个城镇了。<br/>
　　3.	每支军队都可以在任意一个城镇停止征战。<br/>
　　4.	所有军队都很奇怪，他们走的方法有点像国际象棋中的马。不过马每次只能走1*2的路线，而他们只能走R*C的路线。<br/>
　　lanzerb的野心使得他的目标是统一全国，但是兵力的限制使得他们在配备人手时力不从心。假设他们每支军队都能顺利占领这支军队经过的所有城镇，请你帮lanzerb算算至少要多少支军队才能完成统一全国的大业。</div>
# 输入格式

<div class="pdcont">　　第一行包含4个整数M、N、R、C，意义见问题描述。<br/>
　　接下来M行每行一个长度为N的字符串。如果某个字符是&#39;.&#39;，表示这个地方是城镇；如果这个字符时&#39;x&#39;，表示这个地方是高山深涧。</div>
# 输出格式

<div class="pdcont">　　输出一个整数，表示最少的军队个数。</div>
# 样例输入一

<div class="pdcont">　　3 3 1 2<br/>
　　...<br/>
　　.x.<br/>
　　...</div>
# 样例输出一

<div class="pdcont">　　4</div>
# 样例输入二

<div class="pdcont">　　5 4 1 1<br/>
　　....<br/>
　　..x.<br/>
　　...x<br/>
　　....<br/>
　　x...</div>
# 样例输出二

<div class="pdcont">　　5</div>
# 样例说明

<div class="pdcont"><img width="86" height="85" src="source/tsinsen/A1248/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OWdUOEdEajc=.do"/><br/>
<br/>
<img width="113" height="141" src="source/tsinsen/A1248/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9M0FmR3RoMlE=.do"/></div>
# 数据规模和约定

<div class="pdcont">　　30%的数据中，1&lt;=M,N&lt;=4，1&lt;=R,C&lt;=3。<br/>
　　70%的数据中，1&lt;=M&lt;=20，1&lt;=N&lt;=4，1&lt;=R,C&lt;=3。<br/>
　　100%的数据中，1&lt;=M,N&lt;=50，1&lt;=R,C&lt;=10。<br/>
　　100%的数据中，时间限制为1s。</div>

</div>