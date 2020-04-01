<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>PS 国是一个拥有诸多城市的大国，国王 Louis 为城市间的道路修建可谓绞尽脑汁。Louis可以在某些城市之间修建道路，并且在不同城市之间修建道路需要不同的花费。Louis 希望修<span style="">建最少的道路使得国内所有的城市连通。但是由于某些因素，城市之间修建道路需要的花费会</span><span style="">随时改变，Louis 会不断收到道路修建花费被改变的消息，他希望每收到一条消息后能立即知</span><span style="">道使城市连通的最小总花费，Louis决定求助于你来完成这个任务。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是用空格隔开的三个整数N,M,Q，分别表示城市的数目，可以修建的道路的条数，以及收到的消息的个数。接下来有M行，第i+1行是用空格隔开的三个整数Xi,Yi,Zi(1≤Xi,Yi≤N,0≤Zi≤50000000)，表示在城市Xi与城市Yi之间修建道路的花费为Zi。紧接着的Q行，每行是用空格隔开的两个整数Kj和Dj，表示前面输入的第Kj条道路的修建花费被修改为Dj。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含Q行，第i 行输出收到前i 条消息后使城市连通的最小总花费。 &nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 3 <br>1 2 1 <br>2 3 2 <br>3 4 3 <br>4 5 4 <br>5 1 5 <br>1 6 <br>1 1 <br>5 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14 <br>10 <br>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证20%的数据满足N≤1000,M≤6000,Q≤6000。20%的数据满足N≤1000,M≤50000,Q≤8000且修改后的花费不会比之前的花费低。 100%的数据满足N≤20000,M≤50000,Q≤50000。</p>
</div>
</div>