<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一种真菌正在全世界传播。。。</p><p>不过，大家都知道真菌的传染性并不高。</p><p>现在，已知世界地图。世界地图是一张N*M的大矩阵，整个矩阵由‘#’（普通陆地），‘~’（海洋），‘^’（港口），‘*’（机场）组成。其中第a行第b列的点坐标为（a，b）。</p><p>真菌从陆地（陆地包括普通陆地，海洋，港口，下同）能够传播到周围上下左右四个点，但是不能从普通陆地与机场直接进入海洋，同样的，真菌也不能直接从海洋进入普通陆地或机场。但是，真菌能够从海洋进入港口或从港口进入海洋。除此以外，真菌在海洋中的传播法则与在陆地上相同。并且如果真菌感染一个机场，那么全世界所有机场就会在一瞬间被全部感染（神器）！</p><p>真菌传播速度如下表：</p><p><img src="/source/codevs/codevs-5783/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NzgzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE3MDIwOTE1MTkwOV8yNTIucG5n.png" title=""></p><p>第0天时，真菌只感染了位于（x1，y1）的点。</p><p>现在，请求出真菌传播到（x2，y2）需要多少天。</p><p>（如果无解输出"?!"引号不用输出）</p><p><strong>注意：假设世界地图是一个平面</strong></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行N,M,x1,y1,x2,y2。</p><p>接下来是一张N*M的世界地图。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数，表示最短天数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 1 1 5 5</p><p>#*###</p><p>#~~~~</p><p>*^~~~</p><p>#~~^#</p><p>~~~~#</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>一个数，表示最短天数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据，1＜=n,m＜=10；</p><p>100%的数据，1＜=n,m&lt;=2000;</p><p><br></p>
</div>
</div>