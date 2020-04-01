
# Description

<div class="content"><div><span style="font-size: 12pt">    MST</span><span style="font-size: 12pt">（最小生成树）：对于无向带权图&lt;V，E&gt;，若其导出子图的边权和最小，且原图V中对应的任意两个顶点间有且仅有一条通路，则称此图为原图的MST。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">你的任务很简单，对于给定的有向带权图，求出其“最小生成树”，即指定一个根以后，每个点都是从根出发可达的。</span></div>
<div> </div></div>

# Input

<div class="content"><div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">输入文件最多包含3组测试数据，对于每组测试数据：</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">第一行为两个数n,m，表示有向带权图的顶点数和边数，点编号为1~n。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">接下来n行，每行两个整数X_i,Y_i，表示i个顶点在直角坐标系中的坐标。</span></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">接下来m行，每行两个正整数x,y，表示存在一条由点x指向点y的有向边，边权为两顶点的曼哈顿距离（定义见下）。</span></div>
<div> </div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">对于每组测试数据，输出一行：</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">如果不存在“最小生成树”，输出“Poor”；</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">否则输出最小边权和。</span></div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">    3 3<br/>
    0 0<br/>
    1 0<br/>
    2 0<br/>
    1 2<br/>
    1 3<br/>
    2 3<br/>
    3 2<br/>
    0 0<br/>
    1 0<br/>
    2 0<br/>
    1 2<br/>
    3 2<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
Poor<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>    100%的数据，n≤1000，m≤n*n，0≤X_i,Y_i≤10000。<br/><br/>
    可能存在自环。<br/><br/>
 <br/><br/>
【温馨提示】<br/><br/>
对于两个点(a,b)，(c,d)，它们的曼哈顿距离定义如下：<br/><br/>
l=|a-c|+|b-d|</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search= 鸣谢 Hewr"> 鸣谢 Hewr</a></p></div>

