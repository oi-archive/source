<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>D<span style="">博士对物理有着深入的研究，经典物理、天体物理、量子物理都有着以他的名字命名的定理。最近</span><span style="font-family: 'Times New Roman';">D</span><span style="">博士着迷于研究粒子运动的无规则性。对圣经深信不疑的他相信，上帝创造的任何事物必然是有序的、有理可循的，而不是无规则的、混沌的。</span></p>
<p>经过长时间的研究，<span style="font-family: 'Times New Roman';">D</span><span style="">博士找到了很多出现相当频繁的轨迹片断，他把这些轨迹片断储存在一个很大的数据库内。他需要你帮助他写一个程序，对于一个给出的粒子运动轨迹，统计数据库中每个轨迹片断的出现的次数。</span></p>
<p>为清楚起见，我们定义一个粒子的轨迹为二维平面上的一个点列（<span style="font-family: 'Times New Roman';">P</span>1, P2, … PN）。点列<span style="font-family: 'Times New Roman';">P</span><span style="">的一个子列</span><span style="font-family: 'Times New Roman';">[i, j]</span><span style="">定义为</span><span style="font-family: 'Times New Roman';">P</span><span style="">中一段</span>连续的子序列（<span style="font-family: 'Times New Roman';">P</span>i, Pi+1, … Pj）。点列<span style="font-family: 'Times New Roman';">P</span><span style="">的一个子列</span><span style="font-family: 'Times New Roman';">[</span>u, v]被称为点列<span style="font-family: 'Times New Roman';">Q = (Q</span>1, Q2 … Qv-u+1)<span style="">在</span><span style="font-family: 'Times New Roman';">P</span><span style="">中的一次出现，当且仅当</span><span style="font-family: 'Times New Roman';">Q</span><span style="">经过有限次的平移、旋转、翻转、放缩之后得到</span><span style="font-family: 'Times New Roman';">Q</span>’满足<span style="font-family: 'Times New Roman';">Q</span>’k = Pu+k-1（<span style="font-family: 'Times New Roman';">k = 1 </span>… u – v + 1<span style="">）。</span></p>
<p> </p>
<table>
<tbody>
<tr>
<td valign="center" width="568">
<p>对平面<span style="font-family: 'Times New Roman';">X-Y</span><span style="">进行四种操作的解释</span></p>
</td>
</tr>
<tr>
<td valign="center" width="82">
<p>平移</p>
</td>
<td valign="center" width="485">
<p>设平移向量为<span style="font-family: 'Times New Roman';">(dx, dy)</span><span style="">，则任意点</span><span style="font-family: 'Times New Roman';">(x,y)</span><span style="">平移后的结果为</span><span style="font-family: 'Times New Roman';">(x+dx, y+dy)</span></p>
</td>
</tr>
<tr>
<td valign="center" width="82">
<p>旋转</p>
</td>
<td valign="center" width="485">
<p>设旋转角为<span style="font-family: 'Times New Roman';">t</span><span style="">，则任意点</span><span style="font-family: 'Times New Roman';">(x,y)</span><span style="">旋转后的结果为</span></p>
<p>(x cos t – y sin t, x sin t + y cos t)</p>
</td>
</tr>
<tr>
<td valign="center" width="82">
<p>翻转</p>
</td>
<td valign="center" width="485">
<p>任意点<span style="font-family: 'Times New Roman';">(x,y) </span><span style="">翻转后的结果为</span><span style="font-family: 'Times New Roman';">(x, -y)</span></p>
</td>
</tr>
<tr>
<td valign="center" width="82">
<p>放缩</p>
</td>
<td valign="center" width="485">
<p>设放缩比例为<span style="font-family: 'Times New Roman';">p (p </span>≠ 0)，则任意点<span style="font-family: 'Times New Roman';">(x,y)</span><span style="">放缩后的结果为</span><span style="font-family: 'Times New Roman';">(px, py)</span></p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数N、M，分别描述待处理的粒子运动轨迹的点列大小与数据库内的轨迹片断个数。</p>
<p>接下来M行依次给出每个轨迹片断。每行先是一个正整数K，表示该轨迹片断点列的长度。然后2K个整数，依次描述点列中的K个点的横坐标与纵坐标。</p>
<p>接下来一行2N个整数，依次描述待处理的粒子运动轨迹的点列中N个点的横坐标与纵坐标。</p>
<p>注：输入中的每条轨迹中任意相邻两点不会相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">应包含M行，依次给出每个片段在待处理运动轨迹中的出现次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p>
<p>2 17 0 10 1</p>
<p>3 0 0 1 0 1 -1</p>
<p>0 0 1 0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%<span style="">的测试数据，</span>N, M, K ≤ 100<span style="">，片段总长度 </span>≤ 500;</p>
<p>对于50%<span style="">的测试数据，</span>N, M, K ≤ 1 000<span style="">，片段总长度 </span>≤ 5 000;</p>
<p>对于100%<span style="">的测试数据，满足</span>N, K ≤ 200 000，片段总长度 ≤ 200 000<span style="">，输入中给出所有点坐标</span><span style="text-decoration: underline;"><strong>绝对值</strong></span>均不大于<span style="font-family: 'Times New Roman';">10 000</span><span style="">。</span></p>
</div>
</div>