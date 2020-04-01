<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>NAND（与非）是一种二元逻辑运算，其运算结果为真当且仅当两个输入的布尔值不全为真。</p>
<p>NAND运算的真值表如下（1表示真，0表示假）：</p>
<table border="0" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td valign="top" width="270">
<p>输入</p>
</td>
<td valign="top" width="135">
<p>输出</p>
</td>
</tr>
<tr>
<td valign="top" width="135">
<p>A</p>
</td>
<td valign="top" width="135">
<p>B</p>
</td>
<td valign="top" width="135">
<p>C=A NAND B</p>
</td>
</tr>
<tr>
<td valign="top" width="135">
<p>0</p>
</td>
<td valign="top" width="135">
<p>0</p>
</td>
<td valign="top" width="135">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="135">
<p>0</p>
</td>
<td valign="top" width="135">
<p>1</p>
</td>
<td valign="top" width="135">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="135">
<p>1</p>
</td>
<td valign="top" width="135">
<p>0</p>
</td>
<td valign="top" width="135">
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="135">
<p>1</p>
</td>
<td valign="top" width="135">
<p>1</p>
</td>
<td valign="top" width="135">
<p>0</p>
</td>
</tr>
</tbody>
</table>
<p>而两个非负整数的NAND是指将它们表示成二进制数，再在对应的二进制位进行NAND运算。由于两个二进制数的长度可能不等，因此一般约定一个最高位K，使得两个数的二进制表示都不超过K位，不足K位的在高位补零。</p>
<p>譬如12 NAND 9 (K=4)的计算过程如下：</p>
<p>12=(1100)<sub>2</sub> 9=(1001)<sub>2</sub><br>     1100<br><span style="text-decoration: underline;">NAND 1001</span><br>     0111<br>(0111)<sub>2</sub>=7</p>
<p>故12 NAND 9 (K=4) = 7。</p>
<p>容易验证，NAND运算满足交换律但不满足结合律，故计算若干个数的NAND时，应先计算括</p>
<p>号内的，无括号时从左往右计算。</p>
<p>给定N个非负整数A<sub>1</sub>,A<sub>2</sub>……A<sub>N</sub>和约定位数K，利用NAND运算与括号，每个数可以使用任意次，</p>
<p>请你求出范围[L,R]内可以被计算出的数有多少个。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行是用空格隔开的四个正整数<span>N</span>，<span>K</span>，<span>L</span>和<span>R</span></span></p>
<p><span>接下来的一行是<span>N</span>个非负整数<span>A</span></span><sub><span>1</span></sub><span>,A</span><sub><span>2</span></sub><span>……A</span><sub><span>N</span></sub><span>，其含义如上所述。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个整数，表示[L,R]内可以被计算出的数的个数。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><em><strong>Sample 1</strong></em></p>
<p>3 3 1 4<br>3 4 5</p>
<p><em><strong>Sample 2</strong></em></p>
<p>1 3 2 5<br>1</p>
<p><em><strong><br></strong></em></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><em><strong>Sample 1</strong></em></p>
<p>4</p>
<p><em><strong>Sample 2</strong></em></p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例解释</strong></p>
<p>样例1中，(3 NAND 4) NADN (3 NAND 5) = 1，5 NAND 5 = 2，3和4直接可得。 </p>
<p> </p>
<p><strong>数据范围</strong></p>
<p>30%数据，K≤10</p>
<p>70%数据，K≤30</p>
<p>全部数据，<span style="">K≤60，N≤1000， </span><span style="">0≤A</span><sub>i</sub><span style="">≤2</span><sup>K</sup><span style="">-1，1≤L≤R≤10</span><sup>18</sup></p>
</div>
</div>