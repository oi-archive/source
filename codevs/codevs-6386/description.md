<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<pre style="">    在观看完战马检阅之后，来自大草原的两兄弟决心成为超级“马农”，专门饲养战马。
兄弟两回到草原，将可以养马的区域，分为 N * N 的单位面积的正方形，并实地进行考察，归纳出每个单位面积可以养马所获得的收益。接下来就要开始规划他们各自的马场了。
首先，两人的马场都必须是矩形区域。同时，为了方便两人互相照应，也为了防止马匹互相走散，规定两个马场的矩形区域相邻，且只有一个交点。最后，互不认输的两人希望两个马场的收益相当，这样才不会影响他们兄弟的感情。现在，兄弟两找到你这位设计师，希望你给他们设计马场。问共有多少种设计方案？</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<pre style="">    第一行一个整数 N ．表示整个草原的大小为N*N。
接下来 N 行，每行 N 个整数 A（i，j）．表示第 i 行第 j 列的单位草地的收成。
（注意：收益可能是负数，养马也不是包赚的．马匹也可能出现生病死亡等意外。）</pre><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<pre style="word-wrap: break-word; white-space: pre-wrap;">&nbsp;&nbsp;&nbsp;&nbsp;输出符合两人要求的草原分配方案数。</pre><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>1 2 3</p><p>4 5 6</p><p>7 8 9</p>

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
<p><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">40%的数据，N&lt;=10。</span><br style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><br style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">100%的数据，N&lt;=50, -1000&lt;A(i,j)&lt;1000。</span></p>
</div>
</div>