
# Description

<div class="content"><div style="margin: 13pt 0cm"><span style="font-size: medium"><br/>
</span></div>
<div><span style="font-size: medium">世界之树，又称“乾坤树”。在北欧神话中，巨大的树干构成了整个世界。</span></div>
<div><span style="font-size: medium">                                                                                                 ——百度百科</span></div>
<div style="margin: 0cm 0cm 0pt 23.95pt"><span style="font-size: medium">世界树由n个节点构成，共有n-1条枝干连接，任意两个节点都可以互相到达。这一天，主神奥丁准备视察一些树上的种族（比如精灵族，神族，海族，兽族，不死族，还有人族）。但是奥丁只想视察树上的一条路径（不能重复地经过某条枝干），由于他的某种特殊爱好，他还要求路径长度不超过R，且不低于L。已知每条枝干都有一个美丽度，奥丁希望自己视察的路径的美丽度的平均值尽可能地大。</span></div>
<div style="margin: 0cm 0cm 0pt 23.95pt"><span style="font-size: medium">路径美丽度的平均值定义为：将路径上所有枝干的美丽度从小到大排序后，第Trunc(Len/2)+1个美丽度，len指这一条路径的长度。</span></div>
<div style="margin: 0cm 0cm 0pt 23.95pt"><span style="font-size: medium">请你告诉奥丁，他的路径应该从哪个节点出发，到哪个节点结束。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行三个整数：n,L,R</span></div>
<div><span style="font-size: medium">接下来n-1行：</span></div>
<div><span style="font-size: medium">每行三个整数：x, y, z</span></div>
<div><span style="font-size: medium">代表一条连接x节点和y节点的枝干，美丽度为z</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出两个节点u,v，表示从u出发，v结束美丽度最大。</span></div>
<div><span style="font-size: medium">如果有多组答案，任意输出一组。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10  2  5<br/>
2  1  0<br/>
3  2  10<br/>
4  2  5<br/>
5  3  1<br/>
6  4  5<br/>
7  3  10<br/>
8  6  10<br/>
9  6  12<br/>
10  5  0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 9</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
【数据规模及约定】<br/><br/>
对于30%的数据保证：n &lt;= 1000<br/><br/>
对于100%的数据保证：n &lt;= 100000，1 &lt;= L &lt;= R &lt;= n-1，1 &lt;= x,y &lt;= n，<br/><br/>
0 &lt;= z &lt; 2^31，数据保证有解。<br/><br/>
请尽量优化常数。</p><br/>
<p></p><br/>
<p><span style="color: rgb(255, 0, 0);">SPJ程序有误，请不要提交!</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

