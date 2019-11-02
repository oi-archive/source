<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>背景：<br>    &lt;null&gt;_(^q^/∠)_ <br><br>描述：<br>    已知a,b,c, 求满足ax+by=c的整数对(x,y)中x为正整数且最小；</p><p>    若此时0&lt;=x,y，则输出x y，若此时y&lt;0则输出“sometimes naive”（没有双引号）；</p><p>    若没有整数对(x,y)满足条件则输出“too simple”</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入<br>    一行 三个数，a，b，c； <br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出<br/>&nbsp;&nbsp; &nbsp;一行，x y或too simple或sometimes naive&nbsp;<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>    #1<br>    0 0 0</p><p><br></p><p>    #2<br>    2 0 1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>    #1</p><p>    0 0</p><p>    </p><p>    #2</p><p>    too simple<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>    30% 0&lt;=a,b,c&lt;=10;<br>    70% 0&lt;=a,b,c&lt;=500000000;<br>    100% 总之我这个渣渣能过;<br><br></p><p>裸的扩展gcd……<br></p><p>反正long long一定是够的……int……你们试试吧我觉得应该没问题</p>
</div>
</div>