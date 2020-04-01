
# Description

<div class="content"><div>假设有一个n×m的网格。左上角的格子坐标是（1,1），右下角的格子坐标是（n,m）。网格中有k个堵塞的格子，其他的格子是空的。你在空格子（xs，ys）的中心向一个对角线方向（也就是东北，西北，东南，西南）发射一束激光。如果光束碰到堵塞的格子或网格边界，它会反射。在不同情况下光束的反射方式如下图所示。</div>
<div> <img src="/source/bzoj/4235/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOC80MjM1LlBORw==.PNG" width="508" height="159" alt=""/></div>
<div>过了一会儿，光束进入了一个无限的循环。计算至少被光束通过一次的空格子数。我们认为光束通过了一个格子的中心才算是通过了这个格子。</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数n、m、k，接下来k行每行两个整数xi和yi，表示第i个堵塞的格子的坐标。</div>
<div>最后一行两个整数xs，ys和一个字符串表示激光发出的方向。“NE”，“NW”，“SE”，“SW”分别表示方向（-1，1），（-1，-1），（1，1），（1，-1）。</div>
<div>保证输入的堵塞的格子坐标不重复。</div>
<p></p></div>

# Output

<div class="content"><div>一行输出光束至少通过一次的空格子数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 5 3<br/>
3 3<br/>
4 3<br/>
5 3<br/>
2 1 SE</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
</span></div>

# Hint

<div class="content"><p></p><div>100%的数据 n，m，k≤1000000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

