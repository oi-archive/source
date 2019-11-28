<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>地平线(x轴)上有n个矩(lou)形(fang)，用三个整数h[i],l[i],r[i]来表示第i个矩形：矩形左下角为(l[i],0)，右上角为(r[i],h[i])。地平线高度为0。在轮廓线长度最小的前提下，从左到右输出轮廓线。</p>

<img src="/source/codevs/codevs-2995/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzI5OTUuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示矩形个数</p>
<p>以下n行，每行3个整数h[i],l[i],r[i]表示第i个矩形。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行一个整数m，表示节点个数</p>
<p>以下m行，每行一个坐标表示轮廓线上的节点。从左到右遍历轮廓线并顺序输出节点。第一个和最后一个节点的y坐标必然为0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入】</p>
<p>2<br>3 0 2<br>4 1 3</p>
<p>【样例输入2】</p>
<p>5<br>3 -3 0<br>2 -1 1<br>4 2 4<br>2 3 7<br>3 6 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出】</p>
<p>6<br>0 0<br>0 3<br>1 3<br>1 4<br>3 4<br>3 0</p>
<p>【样例输出2】</p>
<p>14<br>-3 0<br>-3 3<br>0 3<br>0 2<br>1 2<br>1 0<br>2 0<br>2 4<br>4 4<br>4 2<br>6 2<br>6 3<br>8 3<br>8 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，n&lt;=100</p>
<p>对于另外30%的数据，n&lt;=100000,1&lt;=h[i],l[i],r[i]&lt;=1000</p>
<p>对于100%的数据，1&lt;=n&lt;=100000,1&lt;=h[i]&lt;=10^9,-10^9&lt;=l[i]&lt;r[i]&lt;=10^9</p>
<p> </p>
</div>
</div>