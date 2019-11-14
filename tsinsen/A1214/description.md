<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　蚂蚁是勤劳的动物，他们喜欢挑战极限。现在他们迎来了一个难题！蚂蚁居住在图书馆里，图书馆里有大量的书籍。书是形状大小质量都一样的矩形。蚂蚁要把这些书摆在水平桌子的边缘。蚂蚁喜欢整洁的布置，所以蚂蚁规定书本必须水平摆放，宽必须平行于桌缘（如图），而且不允许同一高度摆多本书<br/>
<img width="216" height="204" src="source/tsinsen/A1214/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Zk1MRHlOTkE=.do"/><br/>
　　蚂蚁想要让书本伸出桌子边缘尽量远，同时不让书因为重力垮下来。它们已经用不知道什么方法测出了书的长度M（如图）。如果总共有N本书，请你帮忙计算如何摆放使得最多水平伸出桌缘多远。你不用考虑蚂蚁用什么方法搭建这堆书。<br/>
　　如果某本书以上的所有书的重心的竖直射影不在这本书上，或者正好落在在这本书的边界上，那么这堆书是不稳定的，会因为重力而垮下来。<br/>
<br/>
　　(*)不考虑地球自转，重力系数也不因高度改变；<br/>
　　(*)书是质量均匀，质地坚硬的理想二维物体；<br/>
　　(*)在不会垮的前提下，每本书的位置坐标可以是任意实数。</div>
# 输入格式

<div class="pdcont">　　输入文件仅含一行，两个正整数N和M，表示书本数和书本长度。</div>
# 输出格式

<div class="pdcont">　　输出仅包含一行，整数L，表示水平延伸最远的整数距离 (不大于答案的最大整数，详见样例)</div>
# 样例输入

<div class="pddata">1 100</div>
# 样例输出

<div class="pddata">49</div>
# 样例输入

<div class="pddata">2 100</div>
# 样例输出

<div class="pddata">74</div>
# 数据规模和约定

<div class="pdcont">　　10%的数据中N≤5；<br/>
　　20%的数据中N≤10<sup>3</sup>；<br/>
　　40%的数据中N≤10<sup>7</sup>；<br/>
　　100%的数据中N≤10<sup>18</sup>；答案≤10<sup>6</sup>。</div>

</div>