<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">Sdchr有长度为N的数列A。</p><p style="">其他人想了解这个数列，他们会提出m个询问。</p><p style="">每次询问 A[l] xor A[l+1] xor A[l+2] xor ... xor A[r-1] xor A[r] 的值。</p><p style="">Sdchr向会编程的你求助。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行1个数N，表示数列的长度。</p><p style="">第二行N个数，第i个表示A[i]。</p><p style="">第三行1个数m，表示询问个数。</p><p style="">接下来m行，每行两个数l,r，如题目描述计算。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top:5px;margin-right:0;margin-bottom:5px;margin-left: 0">每个询问输出一行。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">4</p><p style="">1 2 3 2</p><p style="">5</p><p style="">1 2</p><p style="">1 3</p><p style="">2 3</p><p style="">3 3</p><p style="">1 4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>0</p><p>1</p><p>3</p><p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">对于30%的数据，1&lt;=N,M&lt;=1000</p><p style="">对于60%的数据，1&lt;=N,M&lt;=10000</p><p style="">对于100%的数据，1&lt;=N,M&lt;=1000000，0&lt;=A[i]&lt;=2^31-1</p><p><strong>数据不保证l&lt;=r</strong></p>
</div>
</div>