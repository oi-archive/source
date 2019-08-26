
# Description

<div class="content"><div>一个W*H的矩形，被分为k=n^2块，且W=nw,H=nh,那么每块满足一下条件 </div>
<div>1.每块是4联通区域 </div>
<div>2.若把矩形均分成k个w*h的矩形，每块可以对应一个矩形，且包含这个矩形四个角的小格（图中黑色部分） </div>
<div>3.每块的格子只能来自对应的矩形，对应矩形相邻的格子，对应矩形相邻矩形内部的格子（图中灰色部分） </div>
<div>4.任意两块之间的分界线不会是直线。 </div>
<div>5.任意一块都在一个（3w-2）*（3*h-2）的格子里，且中心对应2中提及的矩形（图中粗线部分） </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行为k w h </div>
<div>以下k个（3w-2）*（3*h-2）矩形描述每一块情况 </div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出第一行为W H </div>
<div>输出任意一组符合要求的原矩形 </div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 3<br/>
..........<br/>
..........<br/>
...AAAA...<br/>
...AAAAAA.<br/>
...A.AA...<br/>
..........<br/>
..........<br/>
<br/>
..........<br/>
..........<br/>
...BBBB...<br/>
.....BB...<br/>
...BBBB...<br/>
....BB....<br/>
.....B....<br/>
<br/>
..........<br/>
..........<br/>
...C..C...<br/>
..CCC.C...<br/>
...CCCC...<br/>
..........<br/>
..........<br/>
<br/>
..........<br/>
....D.....<br/>
...DDDD...<br/>
...DDD....<br/>
...DDDD...<br/>
..........<br/>
..........</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 6<br/>
AAAABBBB<br/>
AAAAAABB<br/>
ADAABBBB<br/>
DDDDCBBC<br/>
DDDCCCBC<br/>
DDDDCCCC</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>k=N*N</div><br/>
<div>1&lt;=N&lt;=4</div><br/>
<div>3&lt;=W,H&lt;=5</div><br/>
<div>请不要提交，尚无SPJ</div><br/>
</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

