<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: Arial;">给定有n个要相乘的矩阵构成的序列（链）&lt;A1,A2,A3,.......,An&gt;，要计算乘积A1A2.....An。一组矩阵是加全部括号的。矩阵链加括号对运算的性能有很大影响。</p><p style="font-family: Arial;">      仅当两个矩阵A和B相容（即A的列数等于B的行数），才可以进行相乘运算。如果A是一个p×q矩阵，B是q×r矩阵，结果C是p×r的矩阵。计算C的时间由乘法运算次数决定的，次数为p×q×r。</p><p style="font-family: Arial;">      矩阵链乘法问题可表述为：给定n个矩阵构成的一个链&lt;A1，A2，A3.......，An&gt;，其中i=1,2,3,4.....,n，矩阵Ai的维数为Pi-1 ×Pi，对乘积A1A2A3.....An，以一种最小标量乘法次数的方式进行加全部括号。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>如果有n个数组，则第一行输入n+1个整数值</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>所有的数组<span style="font-family: Arial; font-size: 14px; line-height: 26px;">以一种最小标量乘法次数的方式进行加全部括号。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 2 3 4 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>((A1A2)A3)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=100</p><p>1&lt;=Ai&lt;=50</p>
</div>
</div>