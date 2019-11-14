<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在遥远的东方，有一个神秘的民族，自称Y族。他们世代居住在水面上，奉龙王为神。每逢重大庆典，Y族都会在水面上举办盛大的祭祀活动。</p>
<p>我们可以把Y族居住地水系看成一个由岔口和河道组成的网络。每条河道连接着两个岔口，并且水在河道内按照一个固定的方向流动。显然，水系中不会有环流（下图描述一个环流的例子）。</p>
<p> 由于人数众多的原因，Y族的祭祀活动会在多个岔口上同时举行。出于对龙王的尊重，这些祭祀地点的选择必须非常慎重。准确地说，Y族人认为，如果水流可以从一个祭祀点流到另外一个祭祀点，那么祭祀就会失去它神圣的意义。</p>
<p>       族长希望在保持祭祀神圣性的基础上，选择尽可能多的祭祀的地点。</p>

<img src="/source/codevs/codevs-1852/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODUyL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NjA3ODc5OC40MC4yMjg5MzA4NzI1Ni5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件river.in中第一行包含两个用空格隔开的整数<em>N、M</em>，分别表示岔口和河道的数目，岔口从1到<em>N</em>编号。</p>
<p>接下来<em>M</em>行，每行包含两个用空格隔开的整数<em>u</em>、<em>v</em>，描述一条连接岔口<em>u</em>和岔口<em>v</em>的河道，水流方向为自<em>u</em>向<em>v</em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含一个整数<em>K</em>，表示最多能选取的祭祀点的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p>
<p><span style="">1 2</span></p>
<p>3 4</p>
<p>3 2</p>
<p>4 2</p>

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
<h2>【样例说明】</h2>
<p>在样例给出的水系中，不存在一种方法能够选择三个或者三个以上的祭祀点。包含两个祭祀点的测试点的方案有两种：选择岔口1与岔口3，选择岔口1与岔口4。</p>
<p>水流可以从任意岔口流至岔口2。如果在岔口2建立祭祀点，那么任意其他岔口都不能建立祭祀点，但是在最优的一种祭祀点的选取方案中我们可以建立两个祭祀点，所以岔口2不能建立祭祀点。对于其他岔口，至少存在一个最优方案选择该岔口为祭祀点.</p>
<h2>【数据规模】</h2>
<p><em>N</em> ≤ 100</p>
<p><em>M</em> ≤ 1 000</p>
</div>
</div>