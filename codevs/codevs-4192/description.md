<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">applepi <span style="">想进行宇宙旅行。当然，</span>applepi <span style="">知道这是有可能的，因为</span>applepi <span style="">的特殊能力能使他观测到宇宙中的虫洞。所谓虫洞就是一个在三维之外的维度打开的快捷通道，通过虫洞能够从一个地方瞬间移动到另外一个地方。</span></p><p style=""><span style="">为了简化问题，我们建立一个一维坐标系，地球的位置为</span>0<span style="">，而</span>applepi <span style="">的目的地的位置是一个正整数</span>W<span style="">。在每一个单位时间里，</span>applepi<span style="">可以向正方向移动不超过</span>S <span style="">的一个整数。虫洞可以被表示为二元组</span>(B, E)<span style="">，即如果在某次移动之后</span>applepi <span style="">在位置</span>B<span style="">，那么</span>applepi <span style="">就会被立刻传送到位置</span>E<span style="">。注意，</span>applepi <span style="">在移动过程中如果经过位置</span>B<span style="">，由于</span>applepi <span style="">的速度极快是不会被传送的。而且，</span>applepi <span style="">不能够向负方向移动，但是虫洞引起的除外。现在</span>applepi <span style="">想请你帮助他计算一下他至少需要多少个单位时间才能够到达目的地。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入包含多组测试数据。</span></p><p style=""><span style="">每组测试数据的第一行是三个正整数</span>W,S,P<span style="">，表示目的地位置，移动限制和虫洞的数目。</span></p><p style=""><span style="">之后</span>P<span style="">行，每行两个整数</span>B<span style="">和</span>E<span style="">，表示一个虫洞。</span></p><p style=""><span style="">输入文件的最后一行是一个整数 </span>0<span style="">，表示输入的结束。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-left: 28px;"><span style=";font-family:宋体">对于每组测试数据，在单独的一行内输出结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">28 3 5</span></p><p><span style="font-family: 'Courier New';">2 18</span></p><p><span style="font-family: 'Courier New';">5 13</span></p><p><span style="font-family: 'Courier New';">12 6</span></p><p><span style="font-family: 'Courier New';">17 25</span></p><p><span style="font-family: 'Courier New';">20 15</span></p><p><span style="font-family: 'Courier New';">50 6 1</span></p><p><span style="font-family: 'Courier New';">9 45</span></p><p><span style="font-family: 'Courier New';">0</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">4</span></p><p><span style="font-family: 'Courier New';">3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于</span>30% <span style="">的数据，</span>W<span style="">≤</span>1000<span style="">。</span></p><p style=""><span style="">对于 </span>100% <span style="">的数据，</span>W<span style="">≤</span><span style="font-family: 'Times New Roman';">10<sup>9</sup></span><span style="">，</span>2<span style="">≤</span>S<span style="">≤</span>6<span style="">，</span>1<span style="">≤</span>W<span style="">≤</span>40<span style="">，没有</span>B = 0 <span style="">或者</span>B = W <span style="">的虫洞，输入数据保证目的地可达。</span></p><p><br></p>
</div>
</div>