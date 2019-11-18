<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>请写一个程序，要求维护一个数列，支持以下 6 种操作：（请注意，格式栏 中的下划线‘ _ ’表示实际输入文件中的空格）</p>
<table border="0">
<tbody>
<tr>
<td>操作编号</td>
<td>输入文件中的格式</td>
<td>说明</td>
</tr>
<tr>
<td>1. 插入</td>
<td>INSERT_posi_tot_c1_c2_..._ctot </td>
<td>在当前数列的第posi 个数字后插入tot 个数字：c1, c2, …, ctot；若在数列首插 入，则 posi 为 0 </td>
</tr>
<tr>
<td>2. 删除</td>
<td>DELETE_posi_tot </td>
<td>从当前数列的第 posi 个数字开始连续 删除 tot 个数字 </td>
</tr>
<tr>
<td>3. 修改</td>
<td>MAKE-SAME_posi_tot_c </td>
<td>将当前数列的第 posi 个数字开始的连 续 tot 个数字统一修改为 c </td>
</tr>
<tr>
<td>4. 翻转</td>
<td>REVERSE_posi_tot</td>
<td>取出从当前数列的第 posi 个数字开始 的 tot 个数字，翻转后放入原来的位置 </td>
</tr>
<tr>
<td>5. 求和</td>
<td>GET-SUM_posi_tot </td>
<td>计算从当前数列开始的第 posi 个数字 开始的 tot 个数字的和并输出 </td>
</tr>
<tr>
<td>6. 求和最大的子列 </td>
<td>MAX-SUM </td>
<td><br>求出当前数列中和最大的一段子列， 并输出最大和</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第 1 行包含两个数 N 和 M，N 表示初始时数列中数的个数，M 表示要进行的操作数目。 第 2 行包含 N 个数字，描述初始时的数列。 以下 M 行，每行一条命令，格式参见问题描述中的表格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;对于输入数据中的 GET-SUM 和 MAX-SUM 操作，向输出文件依次打印结 果，每个答案（数字）占一行。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 8 2 -6 3 5 1 -5 -3 6 3 <br>GET-SUM 5 4</p>
<p>MAX-SUM</p>
<p>INSERT 8 3 -5 7 2</p>
<p>DELETE 12 1</p>
<p>MAKE-SAME 3 3 2</p>
<p>REVERSE 3 6</p>
<p>GET-SUM 5 4</p>
<p>MAX-SUM</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p>
<p>10</p>
<p>1</p>
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>初始时，我们拥有数列 2 -6 3 5 1 -5 -3 6 3 <br>执行操作GET-SUM 5 4，表示求出数列中从第5个数开始连续4个数字之和，1+(-5)+(-3)+6 = -1： 2 -6 3 5 1 -5 -3 6 3 <br>执行操作 MAX-SUM，表示要求求出当前数列中最大的一段和，应为 3+5+1+(-5)+(-3)+6+3 = 10： 2 -6 3 5 1 -5 -3 6 3 <br>执行 操作 INSERT 8 3 -5 7 2，即在数列中第 8 个数字后插入-5 7 2： 2 -6 3 5 1 -5 -3 6 -5 7 2 3 <br>执行操作 DELETE 12 1，表示删除第 12 个数字，即最后一个： 2 -6 3 5 1 -5 -3 6 -5 7 2 <br>执行操作 MAKE-SAME 3 3 2，表示从第 3 个数开始的 3 个数字，统一修改为 2： 2 -6 3 5 1 -5 -3 6 -5 7 2 改为 2 -6 2 2 2 -5 -3 6 -5 7 2 <br>执行操作 REVERSE 3 6，表示取出数列中从第 3 个数开始的连续 6 个数： <br>2 2 2 -5 -3 6，翻转后得到 6 -3 -5 2 2 2，并放回原来位置： 2 -6 6 -3 -5 2 2 2 -5 7 2 <br>最后执行 GET-SUM 5 4 和 MAX-SUM，不难得到答案 1 和 10。</p>
</div>
</div>