
# Description

<div class="content"><div>给定一个由N个节点，若干条无向边组成的城市，某些节点处有一辆或多辆汽车，一辆汽车只能使用一次，可以行驶任意长度。 </div>
<div>坐车和步行速度不同，坐车每个单位距离需要Ds的时间，步行每个单位距离需要Ws的时间。 </div>
<div>给定一个长度为M的访问列表，要求从0号节点出发，依次访问列表中的每个节点，最后回到0号节点。可以选择坐车或步行，求完成任务所需的最短时间。 </div>
<div>注意：每辆车只能在一次访问中被用一次，而且之后都不能再用了</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数N，M，P </div>
<div>N为点数，M为访问列表长度，P为车辆数。 </div>
<div>第二个M个数，按顺序给出需要访问的点 </div>
<div>第三行P个整数，表示在第X号上有车，一个点可以有多个车。 </div>
<div>第四行到第N+3行，每行N个整数，给出地图，为无向图。 </div>
<div>第i+4行第J+1列的数字Aij表示i号点到J号点的距离。0&lt;=Aij&lt;=200,Aij=0表示没有路 </div>
<div>下面一行两个数字，Ds和Ws分别表示坐车每单位距离所需要的时间和步行每单位距离所要的时间 1保证有解 </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>所需要最小时间</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 1<br/>
2 3<br/>
1<br/>
0 0 1 0<br/>
0 0 0 2<br/>
1 0 0 3<br/>
0 2 3 0<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">36</span></div>

# Hint

<div class="content"><p></p><p>N,M,P&lt;=200</p><br/>
<p>应上传者要求，此题不公开，如有异议，请提出.</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

