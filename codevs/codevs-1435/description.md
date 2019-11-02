<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小<span style="font-family: 'Times New Roman';">Q</span><span style="">在电子工艺实习课上学习焊接电路板。一块电路板由若干个元件组成，我们不妨称之为节点，并将其用数字</span><span style="font-family: 'Times New Roman';">1,2,3</span>….<span style="">进行标号。电路板的各个节点由若干不相交的导线相连接，且对于电路板的任何两个节点，都存在且仅存在一条通路（通路指连接两个元件的导线序列）。</span></p>
<p>在电路板上存在一个特殊的元件称为“激发器”。当激发器工作后，产生一个激励电流，通过导线传向每一个它所连接的节点。而中间节点接收到激励电流后，得到信息，并将该激励电流传向与它连接并且尚未接收到激励电流的节点。最终，激烈电流将到达一些“终止节点”——接收激励电流之后不再转发的节点。</p>
<p>激励电流在导线上的传播是需要花费时间的，对于每条边e，激励电流通过它需要的时间为t<sub>e</sub>，而节点接收到激励电流后的转发可以认为是在瞬间完成的。现在这块电路板要求每一个“终止节点”同时得到激励电路——即保持时态同步。由于当前的构造并不符合时态同步的要求，故需要通过改变连接线的构造。目前小<span style="font-family: 'Times New Roman';">Q</span><span style="">有一个道具，使用一次该道具，可以使得激励电流通过某条连接导线的时间增加一个单位。请问小</span><span style="font-family: 'Times New Roman';">Q</span><span style="">最少使用多少次道具才可使得所有的“终止节点”时态同步？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个正整数N，表示电路板中节点的个数。</p>
<p>第二行包含一个整数S，为该电路板的激发器的编号。</p>
<p>接下来N-1<span style="">行，每行三个整数</span>a , b , t。表示该条导线连接节点a与节点b，且激励电流通过这条导线需要t个单位时间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅包含一个整数V，为小<span style="font-family: 'Times New Roman';">Q</span><span style="font-family: 宋体;">最少使用的道具次数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1</p>
<p>1 2 1</p>
<p>1 3 3</p>

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
<div>
<p>对于<span style="font-family: 'Times New Roman';">40%</span><span style="">的数据，</span>N ≤ 1000</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span>N ≤ 500000</p>
<p>对于所有的数据，t<sub>e</sub> ≤ 1000000</p>
</div>
</div>
</div>