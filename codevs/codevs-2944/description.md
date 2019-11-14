<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　某人去射箭，训练场有一系列的靶子<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_WF97MX0sWF97Mn0sLi4uLFhfe259">，已知某人射中<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_WF97aX0=.latex">的概率为<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_UF97aX0=.latex">。李华会为某人选一段靶子进行射击，但是李华觉得还是不够过瘾，于是他为某人设计了一个记分规则：对于一段连续打中的靶子，设靶子数量为<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TChMXGdlcSZhbXA7c3BhY2U7MSk=.latex">，某人的总分会增加<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PyhMK2EpXGFzdCZhbXA7c3BhY2U7KEwrYik=.latex">，其中<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P2EsYg==.latex">是常数。</p>
<p>　　例如当<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P249JmFtcDtzcGFjZTs4LGE9JmFtcDtzcGFjZTsxLGI9JmFtcDtzcGFjZTsy.latex">时，若某人的射击情况为<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PzExMDExMTAx.latex">，则某人的得分为<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PygyKzEpKigyKzIpKygzKzEpKigzKzIpKygxKzEpKigxKzIpPSZhbXA7c3BhY2U7Mzg=.latex"></p>
<p>　　某人的命中率受多方面影响，很容易变化，李华想知道某一段靶子某人的期望得分。现在要求你支持两个操作：</p>
<ol>
<li>修改：获得两个参数<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_aSxw.latex">，表示<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_UF97aX0=.latex">修改为<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_cA==.latex">。保证<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXEmYW1wO3NwYWNlO2lcbGVxJmFtcDtzcGFjZTtu.latex">，<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MFxsZXEmYW1wO3NwYWNlO3BcbGVxJmFtcDtzcGFjZTsx.latex">。</li>
<li>查询：获得两个参数<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bCxy.latex">，表示询问某人射击<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_WF97aVxpbiZhbXA7c3BhY2U7W2wscl19.latex">的<strong>期望得分</strong>。保证<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXEmYW1wO3NwYWNlO2xcbGVxJmFtcDtzcGFjZTtyXGxlcSZhbXA7c3BhY2U7bg==.latex">。</li>
</ol>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行三个整数<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P24sbSxhLGI=.latex">，表示有<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bg==.latex">个靶子，<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bQ==.latex">个操作，<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P2EsYg==.latex">含义见描述。</p>
<p>　　接下来<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bg==.latex">行，第<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_aQ==.latex">行一个实数，表示<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_UF97aX0=.latex">。保证<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MFxsZXEmYW1wO3NwYWNlO1Bfe2l9XGxlcSZhbXA7c3BhY2U7MQ==.latex">。</p>
<p>　　接下来<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bQ==.latex">行，每行表示一个操作，第一个正整数为<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_dHlwZQ==.latex">。若<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_dHlwZT0x.latex">，则后面有一个正整数<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_aQ==.latex">和一个实数<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_cA==.latex">，若<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_dHlwZT0y.latex">，则后面有两个正整数<img src="/source/codevs/codevs-2944/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bCxy.latex">。参数​含义见描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　每个询问操作对应一行输出，答案均</span><strong>四舍五入强制保留两位小数</strong><span>。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>2 3 1 1
0.5
0.5
2 1 2
1 1 0
2 1 2

</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>4.25
2.00

</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　　对于100%的数据：<img src="/source/codevs/codevs-2944/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PzFcbGVxJmFtcDtzcGFjZTtuLG1cbGVxJmFtcDtzcGFjZTs1MDAwMDAsMFxsZXEmYW1wO3NwYWNlO2EsYlxsZXEmYW1wO3NwYWNlOzM=.latex"></p>
<div> </div>
</div>
</div>