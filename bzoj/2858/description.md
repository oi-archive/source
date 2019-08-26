
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">给出一个有向图，有n个顶点，m条边。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">如果从p到q有一条唯一的路径，则称顶点p可以到达顶点q。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">图中有一个中心点r，它可以到达所有顶点。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"><b>任务</b></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">(A)求出每个顶点能够到达的顶点数量(包括自身)</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">(B)最少加多少条边，使得所有顶点之间均可以相互到达</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第1行:3个整数n(1 n 100,000) , m(1 m 500,000),。顶点编号从1..n编号，有向边编号从1..m编号，R(1 R&lt;n)是图的中心点编号。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">接下来m行，每行2个整数，分别表示一条有向边的开始到结束点</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第1行: 1个整数，分别表示第i个整数可到达的顶点数量。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第2行：1个整数，表示最少需要添加的边的数量X。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">接下来X行，每行2个整数，表示添加的一条有向边。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">11 12 3 <br/>
3 2 <br/>
2 1 <br/>
2 4 <br/>
4 5 <br/>
4 6 <br/>
6 2 <br/>
6 7 <br/>
3 8 <br/>
8 9 <br/>
9 10 <br/>
9 11 <br/>
10 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 6 11 6 1 6 1 4 4 4 1<br/>
5 <br/>
1 3 <br/>
5 4 <br/>
7 6 <br/>
11 9 <br/>
8 3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Ydc提供SPJ">鸣谢Ydc提供SPJ</a></p></div>

