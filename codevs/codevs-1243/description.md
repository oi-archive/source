<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">某学校的校园网由n(1&lt;=n&lt;=50)台计算机组成，计算机之间由网线相连，如图5。其中顶点代表计算机，边代表网线。正如你所见，不同网线的传输能力不尽相同，例如计算机1与计算机2之间传输信息需要34秒，而计算机2与计算机3之间的传输信息只要10秒。计算机1与计算机5之间传输信息需要44秒，途径为机1到机3到机5。</span></p>
<p><span style="">现学校购买了m(1&lt;=m&lt;=10)台加速设备，每台设备可作用于一条网线，使网线上传输信息用时减半。多台设备可用于同一条网线，其效果叠加，即用两台设备，用时为原来的1/4，用三台设备，用时为原来的1/8。如何合理使用这些设备，使计算机1到计算机n传输用时最少，这个问题急需解决。校方请你编程解决这个问题。例如图5，若m=2，则将两台设备分别用于1-3，3-5的线路，传输用时可减少为22秒，这是最佳解。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行先输入n,m。以下n行，每行有n个实数。第i行第j列的数为计算机i与计算机j之间网线的传输用时，0表示它们之间没有网线连接。注意输入数据中，从计算机1到计算机n至少有一条网路。</span></p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p17"><span style="font-size: medium;">输出计算机1与计算机n之间传输信息的最短时间。(保留两位小数)</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 2</span></p>
<p><span style="">0 34 24 0 0</span></p>
<p><span style="">34 0 10 12 0</span></p>
<p><span style="">24 10 0 16 20</span></p>
<p><span style="">0 12 16 0 30</span></p>
<p><span style="">0 0 20 30 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">22.00</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>