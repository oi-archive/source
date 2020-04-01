
# Description

<div class="content"><p><span style="font-size: medium">The pasture contains a small, contiguous grove of trees that has no &#39;holes&#39; in the middle of the it. Bessie wonders: how far is it to walk around that grove and get back to my starting position? She&#39;s just sure there is a way to do it by going from her start location to successive locations by walking horizontally, vertically, or diagonally and counting each move as a single step. Just looking at it, she doesn&#39;t think you could pass &#39;through&#39; the grove on a tricky diagonal. Your job is to calculate the minimum number of steps she must take. Happily, Bessie lives on a simple world where the pasture is represented by a grid with R rows and C columns (1 &lt;= R &lt;= 50, 1 &lt;= C &lt;= 50). Here&#39;s a typical example where &#39;.&#39; is pasture (which Bessie may traverse), &#39;X&#39; is the grove of trees, &#39;*&#39; represents Bessie&#39;s start and end position, and &#39;+&#39; marks one shortest path she can walk to circumnavigate the grove (i.e., the answer): ...+... ..+X+.. .+XXX+. ..+XXX+ ..+X..+ ...+++* The path shown is not the only possible shortest path; Bessie might have taken a diagonal step from her start position and achieved a similar length solution. Bessie is happy that she&#39;s starting &#39;outside&#39; the grove instead of in a sort of &#39;harbor&#39; that could complicate finding the best path. </span></p>
<div><span style="font-size: medium">牧场里有一片树林，林子里没有坑．</span></div>
<div><span style="font-size: medium">    贝茜很想知道，最少需要多少步能围绕树林走一圈，最后回到起点．她能上下左右走，也能走对角线格子．牧场被分成R行C列(1≤R≤50，1≤C≤50)．下面是一张样例的地图，其中“．”表示贝茜可以走的空地，  “X”表示树林，  “*”表示起点．而贝茜走的最近的路已经特别地用“+”表示出来．</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> <img height="209" width="252" alt="" src="/source/bzoj/1656/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8xMSg1KS5qcGc=.jpg"/></span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> </span></div>
<div></div>
<div><span style="font-size: medium">题目保证，最短的路径一定可以找到．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: R and C </span></p>
<p><span style="font-size: medium">* Lines 2..R+1: Line i+1 describes row i with C characters (with no spaces between them). </span></p>
<div><span style="font-size: medium">    第1行输入R和C，接下来R行C列表示一张地图．地图中的符号如题干所述．</span></div></div>

# Output

<div class="content"><p>* Line 1: The single line contains a single integer which is the smallest number of steps required to circumnavigate the grove.</p>
<div><span style="font-size: medium">    输出最少的步数．</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 7<br/>
.......<br/>
...X...<br/>
..XXX..<br/>
...XXX.<br/>
...X...<br/>
......*<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">13</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

