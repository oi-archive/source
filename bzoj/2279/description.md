
# Description

<div class="content"><p>给你一个图。你找一条欧拉回路出来，使得沿这条路转过的角度最小。<br/>
图很特殊，一个结点出来，要么恰好有2条边，或者恰好有4边<br/>
一个欧拉回路，即它必须遍历每个图形的边恰好一次，并回到起 点。 （输入的跑道保证其欧拉回路的存在）.总的转弯弧度就是在这个回路中， 在每个结点处需要的转弯弧度的总和，在一条直线上继续行进不用转弯。每一段 跑道都是可以双向行驶的。</p>
<p></p></div>

# Input

<div class="content"><p>Oneline with 3 &lt; =  N &lt; =  10000{the number of nodes{and N &lt; =  M &lt; =  2N {the number<br/>
of edges.<br/>
N lines with the x and y coordinates o feachnode,inorder.0 &lt; =  x;y &lt; =  10000.The nodes<br/>
have unique coordinate pairs.<br/>
M lines with two space separated numbers i and j,denoting an edge between nodes i and<br/>
j.The nodes are 0-indexed.</p>
<p>第一行 两个数,N , M . (3&lt;=N &lt;=10000, 代表结点的个数。N&lt;=M&lt;=2N 边的个数)<br/>
接下来N行，依次组出每个结点的坐标  0&lt;=x,y&lt;=10000 。每个结点的坐标是唯一 的<br/>
接下来M行,每两个数，表示i, j之间存在一条边.(结点从0开始编号)</p>
<p></p></div>

# Output

<div class="content"><p>欧拉回路上最小的所需转弯的弧度和 <br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">12 19<br/>
1077 2677<br/>
7473 4262<br/>
1095 8844<br/>
84 7875<br/>
7241 7320<br/>
9143 4888<br/>
4524 1947<br/>
4652 1260<br/>
3503 7882<br/>
4692 223<br/>
9745 5245<br/>
2037 2387<br/>
0 1<br/>
0 2<br/>
1 4<br/>
1 2<br/>
1 3<br/>
3 4<br/>
4 6<br/>
4 5<br/>
5 8<br/>
5 6<br/>
5 7<br/>
6 8<br/>
6 7<br/>
7 9<br/>
7 8<br/>
8 9<br/>
9 11<br/>
9 10<br/>
10 11<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">37.699111843077446<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

