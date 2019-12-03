<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定方程 <br>X<sub>1</sub>+X<sub>2</sub>+…+X<sub>n</sub>=m <br>我们对第 1..n1个变量进行一些限制： <br>X<sub>1</sub>≤A<sub>1</sub> <br>X<sub>2</sub>≤A<sub>2</sub> <br>… <br>X<sub>n1</sub>≤A<sub>n1</sub> <br>我们对第 n<sub>1</sub>+1..n<sub>1</sub>+n<sub>2</sub> 个变量进行一些限制： <br>X<sub>n1+1</sub>≥A<sub>n1+1</sub> <br>X<sub>n1+2</sub>≥A<sub>n1+2</sub> <br>… <br>X<sub>n1+n2</sub>≥A<sub>n1+n2</sub> <br>求：在满足这些限制的前提下，该方程正整数解的个数。 <br>答案可能很大，请输出对 p取模后的答案，也即答案除以p的余数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入含有多组数据，第一行两个正整数 T，p。T 表示这个测试点内的数据组数，p 的含义见题目描述。 <br>    对于每组数据，第一行四个非负整数n，n1，n2，m。 <br>    第二行 n1+n2 个正整数，表示 A1..n1+n2。请注意，如果 n1+n2 等于 0，那么这一行会成为一个空行。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共 T行，每行一个正整数表示取模后的答案。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 10007 <br>3 1 1 6 <br>3 3 <br>3 0 0 5 <br> <br>3 1 1 3 <br>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 <br>6 <br>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于第一组数据，三组解为(1,3,2)，(1,4,1)，(2,3,1)。 <br>对于第二组数据，六组解为(1,1,3)，(1,2,2)，(1,3,1)，(2,1,2)，(2,2,1)，(3,1,1)。</p>
<table border="0">
<tbody>
<tr>
<td>测试点编号</td>
<td>n</td>
<td>n1</td>
<td>n2</td>
<td>m</td>
<td>p</td>
</tr>
<tr>
<td>1</td>
<td>n≤5</td>
<td>n1≤8</td>
<td>n2≤8</td>
<td>m≤10</td>
<td>10007</td>
</tr>
<tr>
<td>2</td>
<td>n≤50</td>
<td>0</td>
<td>0</td>
<td>m≤50</td>
<td>262203414</td>
</tr>
<tr>
<td>3</td>
<td>n≤50</td>
<td><span>n1≤8</span></td>
<td>n2≤8</td>
<td>m≤50</td>
<td>437367875 </td>
</tr>
<tr>
<td>4</td>
<td>n≤10<sup>4</sup></td>
<td>0</td>
<td>0</td>
<td><span>m≤10</span><sup>4</sup></td>
<td>10007</td>
</tr>
<tr>
<td>5</td>
<td>n≤10<sup>4</sup></td>
<td><span>n1≤8</span></td>
<td>n2≤8</td>
<td>m≤10<sup>4</sup></td>
<td>10007</td>
</tr>
<tr>
<td>6</td>
<td>n≤10<sup>9</sup></td>
<td><span>n1≤8</span></td>
<td>n2≤8</td>
<td>m≤10<sup>9</sup></td>
<td>10007</td>
</tr>
<tr>
<td>7</td>
<td><span>n≤10</span><sup>9</sup></td>
<td>0</td>
<td>n2≤8</td>
<td>m≤10<sup>9</sup></td>
<td>262203414</td>
</tr>
<tr>
<td>8</td>
<td><span>n≤10</span><sup>9</sup></td>
<td><span>n1≤8</span></td>
<td>n2≤8</td>
<td>m≤10<sup>9</sup></td>
<td>262203414</td>
</tr>
<tr>
<td>9</td>
<td><span>n≤10</span><sup>9</sup></td>
<td>0</td>
<td>0</td>
<td>m≤10<sup>9</sup></td>
<td>437367875</td>
</tr>
<tr>
<td>10</td>
<td><span>n≤10</span><sup>9</sup></td>
<td><span>n1≤8</span></td>
<td>n2≤8</td>
<td>m≤10<sup>9</sup></td>
<td>437367875</td>
</tr>
</tbody>
</table>
<p><br>对于 100%的测试数据：  T≤5，1≤A<sub>1..n1+n2</sub>≤m，n1+n2≤n。  </p>
</div>
</div>