<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明是一个地理学家，经常要对一段河流进行测量分析。他从上游开始向下游方向等距离地选择了N个点测量水位深度。得到一组数据d1,d2,……,dn，回到实验室后数据分析员根据需要对数据进行分析，发掘隐藏在数据背后的规律。最近，小明发现某种水文现象与河床地势有关，于是他指示分析员要找出一段河流中最大高低起伏差不超过K(k&lt;=100)的最长的一段。这看似一个复杂的问题，由于任务紧急，分析员求助于你，并告诉你小明的所有数据，数据都精确到个位。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包含2行，第一行是整数N和k，分别表示测量点的个数和博士要求的最大水深差(也就是河床地势差)。第二行有N个整数，表示从上游开始一次得到的水位深度为di。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，是正数M，表示最长一段起伏不超过K的河流长度，用测量点个数表示。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 2</p>
<p>5 3 2 2 4 5</p>

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
<p><strong>数据范围</strong></p>
<p>         对于100%的数据 有 N &lt;= 30000，di &lt;= 32767以及K &lt;= 100</p>
</div>
</div>