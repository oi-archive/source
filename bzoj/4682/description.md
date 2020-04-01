
# Description

<div class="content"><div>在滑块拼图中，我们通过反复滑动滑块到空格位置来完成一个目标局面。一位拼图设计者结合滑块拼图和迷宫的思</div>
<div>想设计了一种新的拼图。拼图被表示成一个矩形区域，区域被划分成一些 1×1 的小格。其中一些小格被提前放置</div>
<div>了障碍，无法被滑动。剩下的位置里有两个小格是空的，以及一个 2×2 的王滑块与许多 1×1 的卒滑块。如果一</div>
<div>个卒滑块与一个空格相邻，则卒滑块可以移动到空格中。如果一个王滑块的一边两个小格都是空格，则王滑块可以</div>
<div>向这条边的方向移动。但是注意我们无法移动障碍。对于给定的初始拼图，拼图游戏的任务是将王滑块移动到整个</div>
<div>区域的左上角。</div>
<div>例如下图给出了第四组样例的初始局面。</div>
<div> <img src="/source/bzoj/4682/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8xMS5wbmc=.png" width="298" height="150" alt=""/></div>
<div>你的任务是计算从给定局面到完成任务所需的最少移动次数。一次移动是指某种滑块移动到相邻的位置上。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">输入包含多组测试数据。每组数据的第一行包含两个正整数 H 和 W ，表示拼图的矩形区域包含 H×W 个小格。接</div>
<div style="font-size: 11.8181819915771px;">下来 H 行，每行 W 个字符，表示拼图，其中‘X’, ‘o’, ‘*’ 和 ‘.’ 分别表示王滑块、卒滑块、障碍和</div>
<div style="font-size: 11.8181819915771px;">空格。保证 3≤H,W≤50 。输入以两个零作为结束。</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">对于每组数据，输出一行一个整数，如果给定局面能完成任务，则输出最小步数，否则输出-1。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
oo.<br/>
oXX<br/>
.XX<br/>
3 3<br/>
XXo<br/>
XX.<br/>
o.o<br/>
3 5<br/>
.o*XX<br/>
oooXX<br/>
oooo.<br/>
7 12<br/>
oooooooooooo<br/>
ooooo*****oo<br/>
oooooo****oo<br/>
o**ooo***ooo<br/>
o***ooooo..o<br/>
o**ooooooXXo<br/>
ooooo****XXo<br/>
5 30<br/>
oooooooooooooooooooooooooooooo<br/>
oooooooooooooooooooooooooooooo<br/>
o***************************oo<br/>
XX.ooooooooooooooooooooooooooo<br/>
XX.ooooooooooooooooooooooooooo<br/>
0 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
0<br/>
-1<br/>
382<br/>
6807<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

