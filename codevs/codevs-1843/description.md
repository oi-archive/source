<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于N个整数0，1，&amp;hellip;，N-1，一个变换序列T可以将i变成T<sub>i</sub>，其中：T<sub>i</sub>&amp;isin;{0，1，&amp;hellip;，N-1}且U<sub>i=1 to n-1 </sub>{T<sub>i</sub>}={0，1，&amp;hellip;，N-1}。任意x，y&amp;isin;{0，1，&amp;hellip;，N-1}，定义x和y之间的距离D(x，y)=min{|x-y|，N-|x-y|}。给定每个i和T<sub>i</sub>之间的距离D(i，T<sub>i</sub>)，你需要求出一个满足要求的变换序列T。如果有多个满足条件的序列，输出其中字典序最小的一个。</p><p>说明：对于两个变换序列S和T，如果存在p&lt;N，满足：对于i=0，1，&amp;hellip;，p-1，S<sub>i</sub>=T<sub>i</sub>且S<sub>p</sub>&lt;T<sub>p</sub>，我们称S比T字典序小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中的第一行为一个整数N，表示序列的长度。</p><p>接下来的一行为N个整数D<sub>i</sub>，其中：D<sub>i</sub>表示i和T<sub>i</sub>之间的距离。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果至少存在一个满足要求的变换序列T，则输出一行为N个整数，表示你计算得到的字典序最小的T；否则输出&amp;ldquo;No Answer&amp;rdquo;（不含引号）。</p><p>输出文件中相邻两个数字之间用一个空格分开，行末不包含多余空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>1 1 2 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 2 4 0 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，满足：N&lt;=50；</p><p>对于60%的数据，满足：N&lt;=500；</p><p>对于100%的数据，满足：N&lt;=10000。</p>
</div>
</div>