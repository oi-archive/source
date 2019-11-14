<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给一个由小写字母组成的字符串，我们可以用一种简单的方法来压缩其中的重复信息。压缩后的字符串除了小写字母外还可以（但不必）包含大写字母R与M，其中M标记重复串的开始，R重复从上一个M（如果当前位置左边没有M，则从串的开始算起）开始的解压结果（称为缓冲串）。</p>
<p>bcdcdcdcd可以压缩为bMcdRR，下面是解压缩的过程：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="189">
<p>已经解压的部分</p>
</td>
<td valign="top" width="189">
<p>解压结果</p>
</td>
<td valign="top" width="189">
<p>缓冲串</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>b</p>
</td>
<td valign="top" width="189">
<p>b</p>
</td>
<td valign="top" width="189">
<p>b</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>bM</p>
</td>
<td valign="top" width="189">
<p>b</p>
</td>
<td valign="top" width="189">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>bMc</p>
</td>
<td valign="top" width="189">
<p>bc</p>
</td>
<td valign="top" width="189">
<p>c</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>bMcd</p>
</td>
<td valign="top" width="189">
<p>bcd</p>
</td>
<td valign="top" width="189">
<p>cd</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>bMcdR</p>
</td>
<td valign="top" width="189">
<p>bcdcd</p>
</td>
<td valign="top" width="189">
<p>cdcd</p>
</td>
</tr>
<tr>
<td valign="top" width="189">
<p>bMcdRR</p>
</td>
<td valign="top" width="189">
<p>bcdcdcdcd</p>
</td>
<td valign="top" width="189">
<p>cdcdcdcd</p>
</td>
</tr>
</tbody>
</table>
<p>另一个例子是abcabcdabcabcdxyxyz可以被压缩为abcRdRMxyRz。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入仅一行，包含待压缩字符串，仅包含小写字母，长度为<em>n</em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行，即压缩后字符串的最短长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>bcdcdcdcdxcdcdcdcd</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：1&lt;=<em>n</em>&lt;=20</p>
<p>100%的数据满足：1&lt;=<em>n</em>&lt;=50</p>
</div>
</div>