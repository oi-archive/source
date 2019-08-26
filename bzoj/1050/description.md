
# Description

<div class="content"><div>给你一个无向图，N(N&lt;=500)个顶点, M(M&lt;=5000)条边，每条边有一个权值Vi(Vi&lt;30000)。给你两个顶点S和T，求</div>
<div>一条路径，使得路径上最大边和最小边的比值最小。如果S和T之间没有路径，输出”IMPOSSIBLE”，否则输出这个</div>
<div>比值，如果需要，表示成一个既约分数。 备注： 两个顶点之间可能有多条路径。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数，N和M。下来的M行每行包含三个正整数：x，y和v。表示景点x到景点y之间有一条双向公路</div>
<div>，车辆必须以速度v在该公路上行驶。最后一行包含两个正整数s，t，表示想知道从景点s到景点t最大最小速度比</div>
<div>最小的路径。s和t不可能相同。</div>
<div>1&lt;N&lt;=500,1&lt;=x,y&lt;=N，0&lt;v&lt;30000，0&lt;M&lt;=5000</div></div>

# Output

<div class="content"><div>如果景点s到景点t没有路径，输出“IMPOSSIBLE”。否则输出一个数，表示最小的速度比。</div>
<div>如果需要，输出一个既约分数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
4 2<br/>
1 2 1<br/>
3 4 2<br/>
1 4<br/>
【样例输入2】<br/>
3 3<br/>
1 2 10<br/>
1 2 5<br/>
2 3 8<br/>
1 3<br/>
【样例输入3】<br/>
3 2<br/>
1 2 2<br/>
2 3 4<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
IMPOSSIBLE<br/>
【样例输出2】<br/>
5/4<br/>
【样例输出3】<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

