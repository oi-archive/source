<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有些公司是其他公司的部分拥有者，因为他们获得了其他公司发行的股票的一部分。例如，福特公司拥有马自达公司12%的股票。据说，如果至少满足了以下三个条件之一，公司A就可以控制公司B了：</p>
<ol>
<li>公司A = 公司B。</li>
<li>公司A拥有大于50%的公司B的股票。</li>
<li>公司A控制K(K &gt;= 1)个公司，记为C<sub>1</sub>, ..., C<sub>K</sub>，每个公司C<sub>i</sub>拥有x<sub>i</sub>%的公司B的股票，并且x<sub>1</sub>+ .... + x<sub>K</sub> &gt; 50%。</li>
</ol>
<p>给你一个表，每行包括三个数(i,j,p)；表明公司i享有公司j的p%的股票。计算所有的数对(h,s)，表明公司h控制公司s。至多有100个公司。</p>
<p>写一个程序读入N组数(i,j,p)，i,j和p是都在范围(1..100)的正整数，并且找出所有的数对(h,s)，使得公司h控制公司s。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行： N，表明接下来三个数的数量，即(i,j,p)的数量。</p>
<p>第二行到第N+1行： 每行三个整数作为一个三对数(i,j,p)，表示i公司拥有j公司 p%的股份。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出零个或更多个的控制其他公司的公司。每行包括两个整数A、B,表示A公司控制了B公司。将输出的数对以升序排列。</p>
<p>请不要输出控制自己的公司(应该是不输出自己，互相控制的公司还是要输出的）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3
1 2 80
2 3 80
3 1 20</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>1 2
1 3
2 3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>