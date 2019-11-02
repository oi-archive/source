<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>广阔的大海地图可以由矩形阵列表示。 </p><p>矩阵的元素由数字0和1组成。 </p><p>0表示海水。 </p><p>数字1代表军舰。 </p><p>同一舰队的定义为沿军舰数字上下左右还是军舰数字1则为同一舰队。 </p><p>求给定矩形阵列的舰队个数。如:矩阵 </p><p>0111100011 </p><p>1011110100 </p><p>1011100111 </p><p>0000000011 </p><p>有4个舰队。 </p><p>其中有艘军舰发生故障，负责救援的人员从固定的救援军舰赶往故障处。处于安全考虑，救援人员只能通过舰队内部到达故障点。 </p><p><br></p><p>注意： 舰队由军舰构成。^_^ </p><p><br></p><p>本题出自lq。。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>读入n，m （1 &lt; = n，m&lt; ＝ 1000） </p><p>然后是n×m矩阵 </p><p>下来K行有1个询问。为X1,Y1,X2,Y2代表两艘军舰的海上坐标。 </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出：如果两艘军舰属于同一舰队那么输出它们之间最短的内部距离，若两艘军舰不属于同一舰队，那么请输出&quot;Impossible&quot;.&nbsp;</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 10</p><p>0111100011</p><p>1011110100</p><p>1011100111</p><p>0000000011</p><p>1 3 2 6</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（1 &lt; = n，m&lt; ＝ 1000）</p>
</div>
</div>