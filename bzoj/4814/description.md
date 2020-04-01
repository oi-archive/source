
# Description

<div class="content"><div>
<div>小Q是个程序员。众所周知，程序员在写程序的时候经常需要草稿纸。小Q现在需要一张草稿纸用来画图，但是桌上</div>
<div>只有一张草稿纸，而且是一张被用过很多次的草稿纸。草稿纸可以看作一个二维平面，小Q甚至已经给它建立了直</div>
<div>角坐标系。以前每一次草稿使用过的区域，都可以近似的看作一个平面上的一个三角形，这个三角形区域的内部和</div>
<div>边界都不能再使用。当然了，以前的草稿也没有出现区域重叠的情况。小Q已经在草稿纸上画上了一些关键点，这</div>
<div>些关键点都在没使用过的区域。小Q想把这些关键点两两之间尽可能的用线段连接起来。连接两个关键点的线段有</div>
<div>可能会穿过已经用过的草稿区域，这样显然不允许。于是小Q就想知道，有多少对关键点可以被线段连接起来，而</div>
<div>且还不会穿过已经用过的区域。为了方便，小Q保证任意三个关键点不会共线。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数V,T,表示草稿纸上的关键点数量和三角形区域数量。</div>
<div>接下来V行，每行两个整数x,y,表示一个关键点的坐标(x,y)。</div>
<div>接下来T行，每行六个整数x1,y1,x2,y2,x3,y3,表示一个三角形区域的三个顶点坐标分别是(x1,y1),(x2,y2),(x3,y</div>
<div>3)保证三角形的面积大于0。</div>
<div>V&lt;=1000,T&lt;=1000,0&lt;=所有坐标&lt;=10^8且为整数</div></div>

# Output

<div class="content"><div>输出一行，一个整数，表示能够被线段连接起来的关键点有多少对。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 0<br/>
0 0<br/>
2 0<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
整个草稿纸是全新的，任意两个关键点都可以连线。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

