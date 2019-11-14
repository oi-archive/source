<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong><span>现在我们的手头有</span><span>N</span><span>个软件，对于一个软件</span><span>i</span><span>，它要占用</span><span>W<sub>i</sub></span><span>的磁盘空间，它的价值为</span><span>V<sub>i</sub></span><span>。我们希望从中选择一些软件安装到一台磁盘容量为</span><span>M</span><span>计算机上，使得这些软件的价值尽可能大（即</span><span>V<sub>i</sub></span><span>的和最大）。</span><span><br><br></span><span>但是现在有个问题：软件之间存在依赖关系，即软件</span><span>i</span><span>只有在安装了软件</span><span>j</span><span>（包括软件</span><span>j</span><span>的直接或间接依赖）的情况下才能正确工作（软件</span><span>i</span><span>依赖软件</span><span>j)</span><span>。幸运的是，一个软件最多依赖另外一个软件。如果一个软件不能正常工作，那么它能够发挥的作用为</span><span>0</span><span>。</span><span><br><br></span><span>我们现在知道了软件之间的依赖关系：软件</span><span>i</span><span>依赖软件</span><span>D<sub>i</sub></span><span>。现在请你设计出一种方案，安装价值尽量大的软件。一个软件只能被安装一次，如果一个软件没有依赖则</span><span>D<sub>i</sub>=0</span><span>，这时只要这个软件安装了，它就能正常工作。</span><span><br></span></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><strong><span>第</span><span>1</span><span>行：</span><span>N, M</span><span> </span><span><span> </span></span><span>（</span><span>0&lt;=N&lt;=100, 0&lt;=M&lt;=500</span><span>）</span><span><br></span><span><span>      </span></span><span>第</span><span>2</span><span>行：</span><span>W<sub>1</sub>, W<sub>2</sub>, ... W<sub>i</sub>, ..., W<sub>n</sub> </span><span>（</span><span>0&lt;=W<sub>i</sub>&lt;=M</span><span> </span><span>）</span><span><br></span><span><span>      </span></span><span>第</span><span>3</span><span>行：</span><span>V<sub>1</sub>, V<sub>2</sub>, ..., V<sub>i</sub>, ..., V<sub>n</sub> </span><span><span> </span></span><span>（</span><span>0&lt;=Vi&lt;=1000</span><span> </span><span>）</span><span><br></span><span><span>      </span></span><span>第</span><span>4</span><span>行：</span><span>D<sub>1</sub>, D<sub>2</sub>, ..., D<sub>i</sub>, ..., D<sub>n</sub></span><sub><span> </span></sub><span>（</span><span>0&lt;=D<sub>i</sub>&lt;=N, D<sub>i</sub>≠i</span><span> </span><span>）</span><span><br></span></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><strong><strong>一个整数，代表最大价值。</strong></strong></p>
<div><strong><strong><br /></strong></strong></div>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 10<br> 5 5 6<br> 2 3 4<br> 0 1 1 </span></p>
<div><span><br></span></div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>5</span></p>

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