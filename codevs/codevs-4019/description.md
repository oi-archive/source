<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""></span></p><p style=""><span style="">这次小明来到了经典美剧《越狱》的场景里……</span></p><p style=""><span style="">它被抓起来了（</span><span style="font-family: Arial, sans-serif;">-.-</span><span style="">干嘛幻想这么郁闷的场景……）。</span></p><p style=""><span style="">小明身为新一代的</span><span style="font-family: Arial, sans-serif;">Scofield</span><span style="">，在挖了半个月之后终于挖通牢房里的地道。</span></p><p style=""><span style="">在地道里，无数的管道路线困惑了它。（若对情节有任何疑问，请观看原剧）</span><span style="font-family: Arial, sans-serif;"> </span></p><p style=""><span style="font-family: Arial, sans-serif;">   小明</span><span style="">看了看自己的纹身，明白了整个管道网是由</span><span style="font-family: Arial, sans-serif;">N</span><span style="">个小房间和若干小房间之间的单向的管道组成的。</span></p><p style=""><span style="">小房间编号为不超过</span><span style="font-family: Arial, sans-serif;">N</span><span style="">的正整数。</span></p><p style=""><span style="">对于某个管道，小明只能在人品不超过一定程度时通过。</span></p><p style=""><span style="">小明一开始在房间</span><span style="font-family: Arial, sans-serif;">1</span><span style="">，现在小明想知道，每个小房间他最多能够以人品多少的状态到达。</span></p><p style=""><span style="">注意，小明的人品在出发以后是不会改变的。</span></p><p><span style=""></span><br></p><p>                    <br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">每组测试数据的第一行有一个正整数</span>N(1&lt;=N&lt;=2000)<span style="">。</span></p><p><span style="">接下来若干行描述管道，每行三个正整数</span><span style="font-family: 'Times New Roman','serif';">A,B,R(1&lt;=A,B&lt;=N)</span><span style="">，表示</span><span style="font-family: 'Times New Roman','serif';">A</span><span style="">房间有一条到达</span><span style="font-family: 'Times New Roman','serif';">B</span><span style="">房间的管道，且小明的人品不超过</span><span style="font-family: 'Times New Roman','serif';">R</span><span style="">时可以通过（注意从</span><span style="font-family: 'Times New Roman','serif';">B</span><span style="">房间不可由此管道到达</span><span style="font-family: 'Times New Roman','serif';">A</span><span style="">房间，</span></p><p><span style="">即管道是单向的</span>)</p><p><span style="">整个输入数据以一行</span>0 0 0<span style="">结束</span></p><p> </p><p><span style="">特别地，对于</span>30%<span style="">的数据，有</span>N&lt;=100 </p><p>表示<span style="font-family: 'Times New Roman','serif';">A</span><span style="">房间有一条到达</span><span style="font-family: 'Times New Roman','serif';">B</span><span style="">房间的管道，且小明的人品不超过</span><span style="font-family: 'Times New Roman','serif';">R</span><span style="">时可以通过（注意从</span><span style="font-family: 'Times New Roman','serif';">B</span><span style="">房间不可由此管道到达</span><span style="font-family: 'Times New Roman','serif';">A</span><span style="">房间，</span></p><p><span style=""></span><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:14px;font-family:宋体">对每组测试数据输出</span><span style="font-size:14px;font-family:&#39;Times New Roman&#39;,&#39;serif&#39;">N-1</span><span style="font-size:14px;font-family:宋体">行，分别表示对于</span><span style="font-size:14px;font-family:&#39;Times New Roman&#39;,&#39;serif&#39;">2</span><span style="font-size:14px;font-family:宋体">到</span><span style="font-size:14px;font-family:&#39;Times New Roman&#39;,&#39;serif&#39;">N</span><span style="font-size:14px;font-family:宋体">号的小房间，小明最多能够以人品多少的状态到达。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>1 2 30</p><p>1 3 20</p><p>2 3 25</p><p>3 4 30</p><p>2 4 20</p><p>0 0 0</p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30</p><p>25</p><p>25</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1s</p><p><span style=""></span>小明<span style="">最多能够在人品为</span>30<span style="">的情况下到达小房间</span>2(1-&gt;2)</p><p><span style="">小明最多能够在人品为</span>25<span style="">的情况下到达小房间</span>3(1-&gt;2-&gt;3)</p><p><span style="">小明最多能够在人品为</span>25<span style="">的情况下到达小房间</span>4(1-&gt;2-&gt;3-&gt;4)；</p><p><br></p><p><br></p><p><br></p><p><br></p><p> </p><p><br></p><p><br></p>
</div>
</div>