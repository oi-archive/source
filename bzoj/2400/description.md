
# Description

<div class="content"><div style="text-indent: 21pt" align="left">定义无向图中的一条边的值为：这条边连接的两个点的值的异或值。</div>
<div style="text-indent: 21pt" align="left">定义一个无向图的值为：这个无向图所有边的值的和。</div>
<div style="text-indent: 21pt" align="left">给你一个有<span>n个结点m条边的无向图。其中的一些点的值是给定的，而其余的点的值由你决定（但要求均为非负数），使得这个无向图的值最小。在无向图的值最小的前提下，使得无向图中所有点的值的和最小。</span></div>
<div align="left"><b> </b></div></div>

# Input

<div class="content"><div style="text-indent: 21pt" align="left"><span style="color: black">第一行</span><span style="color: black">，</span><span style="color: black">两个数n，m，</span><span style="color: black">表示图的点数和边数</span><span style="color: black">。</span></div>
<div style="text-indent: 21pt" align="left"><span style="color: black">接下来n行</span><span style="color: black">，每行一个数，按编号给出每个点的值（若为负数则表示这个点的值由你决定，值的绝对值大小不超过10^9）。</span></div>
<div style="text-indent: 21pt" align="left"><span style="color: black">接下来m行，每行二个数a，b，表示编号为a与b的两点间连一条边。（保证无重边与自环。）</span></div>
<div style="text-indent: 21pt" align="left"> </div></div>

# Output

<div class="content"><div align="left"><span style="color: black">    </span><span style="color: black">第一行，一个数，表示</span>无向图的值。</div>
<div align="left"><span>    </span>第二行，一个数，表示无向图中所有点的值的和。</div>
<div align="left"> </div></div>

# Sample Input

<div class="content"><span class="sampledata">    3 2<br/>
    2<br/>
    -1<br/>
    0<br/>
    1 2<br/>
    2 3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    2<br/>
    2<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据约定<br/><br/>
  n&lt;=500，m&lt;=2000<br/><br/>
 <br/><br/>
样例解释<br/><br/>
    2结点的值定为0即可。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

