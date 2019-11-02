<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>陶陶为了给一道平面几何题出数据，需要产生 N 个点(x[i],y[i])。已知x,y是由伪随机函数顺序产生，即：</p>
<p>X[i+1] = (X[i]*Ax+Bx+i) mod Cx  (X[1], Ax,Bx,Cx 是事先给定的）</p>
<p>Y[i+1] = (Y[i]*Ay+By+i) mod Cy  (Y[1], Ay,By,Cy 是事先给定的）</p>
<p> </p>
<p>这样，就可以快速连续产生很多点坐标(X[i], Y[i])。</p>
<p>不幸的是，这样产生的点有可能有相同的，虽然这种几率很少，但严谨的陶陶不允许这种事发生。陶陶要求你帮助他解决最少要产生前多少项时，正好有 N 个不相同的点。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行。一个整数 N .</p>
<p>第二行：4个整数 X[1]、 Ax、Bx、Cx .</p>
<p>第三行：4个整数 Y[1]、 Ay、By、Cy .</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数 M 。表示最少要连续产生 M 个点，正好有 N 个不相同的点。数据保证有答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>21</p>
<p>2 4 3 6</p>
<p>5 2 3 13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>24</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>数据范围：</strong></p>
<p>  1&lt;=N&lt;=1,000,000, 其它所有数据都在[1...1,000,000,000]范围内。</p>
</div>
</div>