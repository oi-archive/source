<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明最近在为线性代数而头疼，线性代数确实很抽象（也很无聊），可惜他的老师正在讲这矩阵乘法这一段内容。<br>当然，小明上课打瞌睡也没问题，但线性代数的习题可是很可怕的。小明希望你来帮他完成这个任务。</p>
<p>现在给你一个ai行aj列的矩阵和一个bi行bj列的矩阵，要你求出他们相乘的积（当然也是矩阵）。<br>(输入数据保证aj=bi,不需要判断)</p>
<p>矩阵乘法的定义：</p>
<p>1. 矩阵A乘以B的时候，必须要求A的列数=B的行数，否则无法进行乘法运算。因此矩阵乘法也不满足交换律。</p>
<p>2. 设A是X*N的矩阵，B是N*Y的矩阵，用A的每一行乘以B的每一列，得到一个X*Y的矩阵。对于某一行乘以某一列的运算，我们称之为向量运算，即对应位置的每个数字相乘之后求和。</p>
<p>写为公式及：</p>
<p>C[i,j] = Sigma(A[i,k] * B[k,j])</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共有ai+bi+2行，并且输入的所有数为整数（long long范围内）。<br>第1行：ai 和 aj<br>第2~ai+2行：矩阵a的所有元素<br>第ai+3行：bi 和 bj<br>第ai+3~ai+bi+3行：矩阵b的所有元素</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出矩阵a乘矩阵b的积（矩阵c)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2<br>12 23<br>45 56<br>2 2<br>78 89<br>45 56</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1971 2356<br>6030 7141</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>矩阵大小&lt;=200*200</p>
</div>
</div>