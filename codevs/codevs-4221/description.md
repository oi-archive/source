<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Mz喜欢晨跑，他的社区里有N个路口，有N-1条小路将它们连接，每条小路都有一定的长度。Mz每次选择一个路口出发，沿着小路跑向其他的路口。Mz晨跑的时候从来不会往回跑，也就是说他每次从不会经过相同的小路。Mz最后会因为周围已经没有未跑过的小路而停下，除此情况之外他是不会停下的。Mz希望每次晨跑的路径都不同，两条路径相同当且仅当路径上的每个路口依次相同。Mz想知道当他跑尽所有不同的路径时，他所跑过的总长度是多少。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个正整数N，表示有N个路口。</p><p>接下来N-1行，每行三个整数k,x,y，表示有一条长度为k的小路连接x号和y号路口。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，表示当他跑尽所有不同路径时，他所跑过的总长度。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>10 1 2</p><p>20 1 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>90<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：</p><p>所有不同路径分别是1-2，1-3，2-1-3，3-1-2，长度分别为10，20，30，30。例如路径2-1-3-1不是合法的因为它包含了重复的边，而路径2-1是不合法的因为当到达1号路口时还有小路可跑。</p><p>数据范围：</p><p>对于40%的数据，N&lt;=2,000。</p><p>对于100%的数据，0&lt;N&lt;=200,000，0&lt;=k&lt;100，0&lt;x&lt;=N，0&lt;y&lt;=N。</p><p><br></p>
</div>
</div>