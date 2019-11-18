<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个三角形木板,竖直立放，上面钉着n(n+1)/2颗钉子，还有(n+1)个格子（当n=5时如图1）。每颗钉子和周围的钉子的距离都等于d，每个格子的宽度也都等于d，且除了最左端和最右端的格子外每个格子都正对着最下面一排钉子的间隙。</p>
<p>让一个直径略小于d的小球中心正对着最上面的钉子在板上自由滚落，小球每碰到一个钉子都可能落向左边或右边（概率各1/2），且球的中心还会正对着下一颗将要碰上的钉子。例如图2就是小球一条可能的路径。</p>
<p>我们知道小球落在第i个格子中的<strong>概率</strong>p<sub>i</sub><strong>=               </strong>，其中i为格子的编号，从左至右依次为0,1,...,n。</p>
<p>现在的问题是计算拔掉某些钉子后，小球落在编号为m的格子中的概率p<sub>m</sub>。假定最下面一排钉子不会被拔掉。例如图3是某些钉子被拔掉后小球一条可能的路径。</p>

<img src="/source/codevs/codevs-1709/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzA5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTIzMDE0Ni40OTAuNjExMjU0NjEyODc0LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行为整数n（2&lt;=n&lt;=50）和m（0&lt;=m&lt;=n）。以下n行依次为木板上从上至下n行钉子的信息，每行中‘*’表示钉子还在，‘.’表示钉子被拔去，注意在这n行中空格符可能出现在任何位置。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，是一个既约分数<span lang="EN-US">(0</span>写成<span lang="EN-US">0/1)</span>，为小球落在编号为<span lang="EN-US">m</span>的格子中的概<span lang="EN-US">p<sub>m</sub></span>。既约分数的定义：<span lang="EN-US">A/B</span>是既约分数，当且仅当<span lang="EN-US">A</span>、<span lang="EN-US">B</span>为正整数且<span lang="EN-US">A</span>和<span lang="EN-US">B</span>没有大于<span lang="EN-US">1</span>的公因子。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5 2<br>
<br>
</pre>
<pre> </pre>
<pre>*<br>
<br>
</pre>
<pre>   * .<br>
<br>
</pre>
<pre>  * * *<br>
<br>
</pre>
<pre> * . * *<br>
<br>
</pre>
<p>* * * * *</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>7/16</span></p>

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