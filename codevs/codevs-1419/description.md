<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，藤原妹红是拥有不老不死能力的人类。虽然不喜欢与人们交流，妹红仍然保护着误入迷途竹林村民。由于算得上是幻想乡最强的人类，对于她而言，迷途竹林的单向道路亦可以逆行。在妹红眼中，迷途竹林可以视为一个由N个路口(编号1..N)，M条不同长度双向路连接的区域。妹红所在的红之自警队为了方便在迷途竹林中行动，绘制了一张特殊的迷途竹林地图，这张地图上只保留了N-1条道路，这些道路保证了任意两个路口间有且仅有一条路径，并且满足所有保留的道路长度之和最小，我们称这些道路为『自警队道路』。现在妹红打算在其中一个连接有多条『自警队道路』的路口设立根据地，当去掉根据地这个根据地所在路口后，就会出现某些路口间无法通过『自警队道路』相互连通的情况，我们认为这时仍然能够通过『自警队道路』连通的路口属于同一个『区域』。妹红希望最后每个『区域』的『自警队道路』总长尽可能平均，请计算出她应该选择哪一个路口作为根据地。<br> 　　下例中红色的路口为妹红选择的根据地，实线边表示『自警队道路』，绿色虚线边表示非『自警队道路』，数字表示边权，『自警队道路』中相同颜色的实线边代表属于同一个『区域』：<br> 　　<br> 　　(尽可能平均即权重最小，设每一块『区域』的路线总长为Length[i]，平均路线长度为Avg=SUM{Length[i]}/区域数，权重d=∑( (Length[i]-Avg)^2 ) )</p>

<img src="/source/codevs/codevs-1419/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNDE5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2Mzk1NTA2OS40MzAuNTEyNzU0Nzk1MzcyLmdpZg==.gif" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：2个正整数N,M<br> 　　第2..M+1行：每行2个整数u,v和1个实数len，表示u,v之间存在长度为len的边</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：1个整数，最后选择的路口编号，存在多个可选路口时选择编号小的</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br> 3 1 5<br> 3 2 4<br> 1 2 3</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于60%的数据：3 ≤ N ≤ 2,000，N-1 ≤ M ≤ 50,000<br> 　　对于100%的数据：3 ≤ N ≤ 40,000，N-1 ≤ M ≤ 200,000<br> 　　对于100%的数据：0 &lt; len ≤ 100,000,000<br>　提示<br>　　样例解释：<br> 　　妹红的『自警队道路』为(1,2)和(2,3)。<br> 　　只能选择2作为根据地，产生的两个区域Length[i]分别为3和4。<br> 　　所以方差为：(4-3.5)^2 + (3-3.5)^2 = 0.5<br><br> 　　注意：<br> 　　保证不存在相同距离的线路，两个路口间可能出现多条路径，且任意点对间至少存在一条路径。</p>
</div>
</div>