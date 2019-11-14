<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定7个整数N,A<sub>0</sub>,B<sub>0</sub>,L<sub>0</sub>,A<sub>1</sub>,B<sub>1</sub>,L<sub>1</sub>，要求设计一个01串S=s<sub>1</sub>s<sub>2</sub>…s<sub>i</sub>…s<sub>N</sub>，满足：</p>
<ol>
<li>s<sub>i</sub>=0或s<sub>i</sub>=1，1&lt;=i&lt;=N；</li>
<li>对于S的任何连续的长度为L<sub>0</sub>的子串s<sub>j</sub>s<sub>j+1</sub>…s<sub>j+L0-1</sub>(1&lt;=j&lt;=N-L<sub>0</sub>+1)，0的个数大于等于A<sub>0</sub>且小于等于B<sub>0</sub>;</li>
<li>对于S的任何连续的长度为L<sub>1</sub>的子串s<sub>j</sub>s<sub>j+1</sub>…s<sub>j+L1-1</sub>(1&lt;=j&lt;=N-L<sub>1</sub>+1)，1的个数大于等于A<sub>1</sub>且小于等于B<sub>1</sub>;</li>
</ol>
<p>例如，N=6,A<sub>0</sub>=1,B<sub>0</sub>=2,L<sub>0</sub>=3,A<sub>1</sub>=1,B<sub>1</sub>=1,L<sub>1</sub>=2，则存在一个满足上述所有条件的01串S=010101。</p>
<p><span style="font-weight: 800;"><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅一行，有<span>7</span>个整数，依次表示<span>N,A<sub>0</sub>,B<sub>0</sub>,L<sub>0</sub>,A<sub>1</sub>,B<sub>1</sub>,L<sub>1</sub></span>，相邻两个整数之间用一个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，若不存在满足所有条件的<span lang="EN-US">01</span>串，则输出一个整数<span lang="EN-US">-1</span>，否则输出一个满足所有条件的<span lang="EN-US">01</span>串。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6 1 2 3 1 1 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>010101</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>3&lt;=N&lt;=1000</span>，<span>1&lt;= A<sub>0</sub>&lt;=B<sub>0</sub>&lt;=L<sub>0</sub>&lt;=N</span>，<span>1&lt;=A<sub>1</sub>&lt;=B<sub>1</sub>&lt;=L<sub>1</sub>&lt;=N</span></p>
</div>
</div>