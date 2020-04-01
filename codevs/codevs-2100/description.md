<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　女之耽兮，犹可说也；士之耽兮，不可说也！ 　　“跪棹兮兰桨，击空明兮溯流光；渺渺兮予怀，望美人吸天一方～～～～” 　　看到这样的场面，WZH不禁想起了WZH的女神GM…… 　　地图可以用一个N×M的平面直角坐标系表示。WZH家在左下角(1,1)，GM家在右上角(N,M)，从左下角到右上角布满了网格状的双向道路。也就是说，每条道路的方向都平行于坐标轴，长度均为1。 　　每条道路都有其可走次数。每一次，WZH可以选择任何一条路径（如果有）从WZH家到GM家，再回到WZH家，这叫做一次往返。注意如果去程与回程经过了同一道路，则视为走了这条道路2次。 　　求WZH能够进行往返的最大次数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个正整数<span style="font-family: 'Lucida Console';">N</span><span style="">，</span><span style="font-family: 'Lucida Console';">M</span><span style="">，以空格隔开。</span></p>
<p>接下来<span style="font-family: 'Lucida Console';">N</span><span style="">行，每行</span><span style="font-family: 'Lucida Console';">M-1</span><span style="">个自然数，表示</span><span style="font-family: 'Lucida Console';">N(M-1)</span><span style="">条纵向边。其中第</span><span style="font-family: 'Lucida Console';">i</span><span style="">行的第</span><span style="font-family: 'Lucida Console';">j</span><span style="">个数</span><span style="font-family: 'Lucida Console';">W</span>ij表示，从<span style="font-family: 'Lucida Console';">(i,j)</span><span style="">到</span><span style="font-family: 'Lucida Console';">(i,j+1)</span><span style="">有一条可以走</span><span style="font-family: 'Lucida Console';">W</span>ij次的双向道路。</p>
<p>接下来<span style="font-family: 'Lucida Console';">M</span><span style="">行，每行</span><span style="font-family: 'Lucida Console';">N-1</span><span style="">个自然数，表示</span><span style="font-family: 'Lucida Console';">M(N-1)</span><span style="">条横向边。其中第</span><span style="font-family: 'Lucida Console';">k</span><span style="">行的第</span><span style="font-family: 'Lucida Console';">l</span><span style="">个数</span><span style="font-family: 'Lucida Console';">W</span>kl表示，从<span style="font-family: 'Lucida Console';">(l,k)</span><span style="">到</span><span style="font-family: 'Lucida Console';">(l+1,k)</span><span style="">有一条可以走</span><span style="font-family: 'Lucida Console';">W</span>kl次的双向道路。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共一行，为一个整数，即最大往返次数。</p>

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
<p>23</p>
<p>233</p>
<p>1</p>
<p>2333 233</p>
<p>0 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
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
<p>WZH<span style="">可以先走</span><span style="font-family: 'Lucida Console';">2333--233--2</span><span style="">去找</span><span style="font-family: 'Lucida Console';">GM</span><span style="">，然后按原路返回。</span><span style="font-family: 'Lucida Console';">WZH</span><span style="">不能再去</span><span style="font-family: 'Lucida Console';">GM</span><span style="">家了，因为如果再去就回不来了。</span></p>
<p> </p>
<p>对于10%<span style="">的数据，</span>M,N≤2。</p>
<p> </p>
<p>对于20%<span style="">的数据，</span>M,N≤3。</p>
<p> </p>
<p>对于30%<span style="">的数据，</span>M,N≤4。</p>
<p> </p>
<p>对于40%<span style="">的数据，</span>M,N≤5。</p>
<p> </p>
<p>对于50%<span style="">的数据，</span>M,N≤6。</p>
<p> </p>
<p>对于60%<span style="">的数据，</span>M,N≤8。</p>
<p> </p>
<p>对于70%<span style="">的数据，</span>M,N≤23。</p>
<p> </p>
<p>对于80%<span style="">的数据，</span>M,N≤33。</p>
<p> </p>
<p>对于100%<span style="">的数据，</span>M,N≤233<span style="">，</span><span style="font-family: 'Lucida Console';">0</span>≤<span style="font-family: 'Lucida Console';">W</span>ij,Wkl≤23333。</p>
<p><span style=""><br></span></p>
</div>
</div>