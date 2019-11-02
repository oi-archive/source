<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>古斯迪尔文明曾在约10亿年前在地球上辉煌一时，尤其在历法、数学、天文等方面的发展水平已经超过现代。在古城的众多庙宇中，考古人员都发现了一种奇特的建筑，该建筑包含一排独立的房间。 <br>以下是一个规模较小的建筑的内部结构，包括9个房间：<br>在每个房间的中央，挂有一个转盘，每个转盘分为6个格子，每个格子写着一个1到9的数字。转盘可以逆时针转动。转盘的红色标记始终指向上方的格子。每个房间的转盘都不相同。 <br>CC考古工作室近日成功地破译了当时的文字，对进一步研究古斯迪尔文明作出了重要贡献。首先，研究人员翻译了当时的宗教书籍，得知了建筑的用途。 原来每个寺院都要在建成以后每隔若干年举行一次大型的庆典。由于?天机不可泄漏?，寺院方面并不直接说明庆典的日期，而是采用暗示的方法。奇特的建筑 就是为了确定庆典的日期而专门建造的。 <br>房间从左到右编号为1，2，3，卬，同时寺院有n个祭司也从1到n编号，这些祭司每年到房间中祈祷一次。建寺那年祭司和自己编号相同的房间祈祷。 同时，转盘上红色标记指示的格子的数字就是该祭司第二年祈祷的房间编号。在祭司祈祷完毕以后，将转盘逆时针旋转一格。转盘的设计使得在每年祈祷时，每个房 间只有一个祭司。 <br>从建寺以后，当某一年祈祷时，每个祭司的编号都和祈祷房间的编号相同时，就是举行庆典的日期。实际上，每隔若干年，就会有一次庆典。 <br>作为CC考古工作室的首席软件顾问，你负责编程求出第一次举行庆典的确切日期。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>文件第一行是两个整数n，p，n表示房间的数目（也就是祭司的数目），p表示转盘包含的格子的数目。(0 &lt; n, p &lt;= 200) <br>以下有n行，每行p个整数，表示每个房间转盘的格子上的数字。每行第一个数表示寺院建立时红色标记指向的数字，以下的数字按照顺时针方向给出。</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，表示第一次举行庆典是在建寺以后多少年。如果永远不会出现符合条件的情况或者第一次符合条件的年份超过10^9（那时古斯迪尔文明已经衰落了），则输出'No one knows.'</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>6 3
2 6 3
1 1 1
4 4 6
6 3 5
3 2 2
5 5 4
</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>不要想水过，竟然下我的程序，我开始只是没有好数据而已</p>
</div>
</div>