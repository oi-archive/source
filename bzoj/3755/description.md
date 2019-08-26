
# Description

<div class="content"><div>在Pty学校附近，有一座名之为岳之麓的高山。Pty很喜欢和（哔——）一起爬山。</div>
<div>山的平面模型如下：</div>
<div>山由一个顶点集：A1,A2…An给定，保证Ai的x单调递增。我们将Ai和Ai+1之间连上线段，表示山的某一段。如下图所示：</div>
<div><img src="source/bzoj/3755/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMS9hYWEuR0lG.GIF" width="471" height="344" alt=""/></div>
<div> </div>
<div>Pty想要爬到这座山的最高的顶点，当两个顶点的高度相同时，我们认为x比较大的顶点要高一些。Pty不是盲人，所以他将会在爬山时采取一些策略，使得他能够尽量快的到达最高的顶点。</div>
<div>Pty从初始的顶点出发，往左右看去，他将朝他能够看到的最高的顶点方向走去。当走到每一个顶点时，他都会重新观察，如果这时看到的顶点比之前看到的顶点还要高，那么他将选择此时看到的顶点走去，直到他到达最高点为止。</div>
<div>例如上图中：Pty从A4点出发。他能够看到的最高点是A6，所以他将会向右侧走去。当他到达A5号点时，能够看到A1点比A6点更高，所以他会调转方向，向左侧走去。由于A1是最高的顶点，所以他将一直往左侧走，直到到达A1为止。</div>
<div>Pty想知道从每一个顶点出发，分别需要走过多少段才能到达最高点。例如上图中从A4出发需要走过5段才能到达最高点。</div>
<p></p></div>

# Input

<div class="content"><div>第一行输入n，表示n个顶点。</div>
<div>接下来n行，每行两个整数xi, yi，表示第i个顶点的坐标。</div>
<div>输入保证xi单调递增。</div>
<p></p></div>

# Output

<div class="content"><div>输出共n行：第i行表示从第i个顶点出发走到最高点需要经过多少步。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 5<br/>
2 4<br/>
3 9<br/>
4 0<br/>
5 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
0<br/>
1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><div><img src="source/bzoj/3755/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMS9iYmIuZ2lm.gif" width="412" height="364" alt=""/></div><br/>
<div>100%的数据满足：n&lt;=200000, xi&lt;=10^6, yi&lt;= 10^6</div><br/>
<div></div><br/>
<div><span style="color: rgb(255, 0, 0);">此题存在版权，故不再支持提交，保留在此只供大家参考题面！ 望见谅！</span></div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

