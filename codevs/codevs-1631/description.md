<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>组合数<span style="font-family: Calibri;">C(N, K)</span><span style="">表示了</span><span style="font-family: Calibri;">N</span><span style="">个数字不重复地选取</span><span style="font-family: Calibri;">K</span><span style="">个作组合的方案数。</span></p>
<p>C(N, K) = N!/(N-M)!M!</p>
<p>当然，在取余数的条件下，由于除法的限制，上述公式求<span style="font-family: Calibri;">C(N, K) mod H</span><span style="">不方便，并且高精度除法也不容易写，所以一般情况下我们采取的是下列方法。</span></p>
<p>若<span style="font-family: Calibri;">N</span><span style="">，</span><span style="font-family: Calibri;">K</span><span style="">不大，可以通过递推的方法求出所有组合数。</span></p>
<p>首先，<span style="font-family: Calibri;">N</span><span style="">个数取</span><span style="font-family: Calibri;">0</span><span style="">个数显然只有</span><span style="font-family: Calibri;">1</span><span style="">种方案，那就是什么都不取；</span></p>
<p>接着，<span style="font-family: Calibri;">N</span><span style="">个数取</span><span style="font-family: Calibri;">N</span><span style="">个数的组合显然也只有</span><span style="font-family: Calibri;">1</span><span style="">种方案。</span></p>
<p>所以<span style="font-family: Calibri;">C(N, 0) = 1</span><span style="">，</span><span style="font-family: Calibri;">C(N, N) = 1</span></p>
<p>其他情况下，<span style="font-family: Calibri;">C(N, K) = C(N - 1, K) + C(N </span>– 1, K – 1)<span style="">，这样就可以通过递推求出所有组合数。</span></p>
<p>你可以看到，其实结果其实就是杨辉三角形。</p>
<p>现在对于给定的<span style="font-family: Calibri;">N</span><span style="">和</span><span style="font-family: Calibri;">K</span><span style="">，请输出</span><span style="font-family: Calibri;">C(N, K) mod </span>100003。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件<span style="font-family: Calibri;">com</span>.in的第1行为两个非负整数<span style="font-family: Calibri;">N</span><span style="">，</span><span style="font-family: Calibri;">K</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件<span style="font-family: Calibri;">com</span>.out包括1个非负整数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】</p>
<p>对于100%的数据，<span style="font-family: Calibri;">N</span><span style="">≤</span><span style="font-family: Calibri;">1000</span><span style="">，</span><span style="font-family: Calibri;">K</span><span style="">≤</span>1000<span style="">。</span></p>
</div>
</div>