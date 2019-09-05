# 题目描述


<p>
<span style="font-size:13px;line-height:19px;"> </span> 
</p>
<p style="margin-left:0px;">
【问题描述】
</p>
<p style="margin-left:0px;">
请写一个程序，要求维护一个数列，支持以下 6 种操作：（请注意，格式栏 中的下划线‘ _ ’表示实际输入文件中的空格）
</p>
<table border="1" cellpadding="0" cellspacing="0" style="font-size:13px;color:black;background-color:white;">
<tbody>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
操作编号
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
输入文件中的格式
</p>
</td>
<td valign="top" width="276">
<p align="center" style="margin-left:0px;">
说明
</p>
</td>
</tr>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
1.  插入
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
<span>INSERT_<em>posi</em>_<em>tot</em>_<em>c</em>1_<em>c</em>2_..._<em>c</em></span><em><span>tot</span></em> 
</p>
</td>
<td valign="top" width="276">
<p style="margin-left:0px;">
<span>在当前数列的第 </span><em><span>posi </span></em><span>个数字后插入 </span><em><span>tot</span></em> 
</p>
<p style="margin-left:0px;">
<span>个数字：</span><em><span>c</span></em><span>1, <em>c</em>2, …, <em>c</em></span><em><span>tot</span></em><span>；若在数列首插</span> 
</p>
<p style="margin-left:0px;">
<span>入，则 </span><em><span>posi </span></em><span>为 0</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
2.  删除
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
DELETE_<em>posi</em>_<em>tot</em> 
</p>
</td>
<td valign="top" width="276">
<p style="margin-left:0px;">
<span>从当前数列的第 </span><em><span>posi </span></em><span>个数字开始连续</span> 
</p>
<p style="margin-left:0px;">
<span>删除 </span><em><span>tot </span></em><span>个数字</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
3.  修改
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
MAKE-SAME_<em>posi</em>_<em>tot</em>_<em>c</em> 
</p>
</td>
<td valign="top" width="276">
<p style="margin-left:0px;">
<span>将当前数列的第 </span><em><span>posi </span></em><span>个数字开始的连</span> 
</p>
<p style="margin-left:0px;">
<span>续 </span><em><span>tot </span></em><span>个数字统一修改为 </span><em><span>c</span></em> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
4.  翻转
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
REVERSE_<em>posi</em>_<em>tot</em> 
</p>
</td>
<td valign="top" width="276">
<p style="margin-left:0px;">
<span>取出从当前数列的第 </span><em><span>posi </span></em><span>个数字开始</span> 
</p>
<p style="margin-left:0px;">
<span>的 </span><em><span>tot </span></em><span>个数字，翻转后放入原来的位置</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
5.  求和
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
GET-SUM_<em>posi</em>_<em>tot</em> 
</p>
</td>
<td valign="top" width="276">
<p style="margin-left:0px;">
<span>计算从当前数列开始的第 </span><em><span>posi </span></em><span>个数字</span> 
</p>
<p style="margin-left:0px;">
<span>开始的 </span><em><span>tot </span></em><span>个数字的和并输出</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="91">
<p style="margin-left:0px;">
6.  求和最
</p>
<p style="margin-left:0px;">
大的子列
</p>
</td>
<td valign="top" width="217">
<p style="margin-left:0px;">
<br/>
</p>
<p style="margin-left:0px;">
MAX-SUM
</p>
</td>
<td valign="top" width="276">
<p style="margin-left:0px;">
求出当前数列中和最大的一段子列，
</p>
<p style="margin-left:0px;">
并输出最大和
</p>
</td>
</tr>
</tbody>
</table>
<p style="margin-left:0px;">
【输入格式】
</p>
<p style="margin-left:0px;">
输入文件的第 1 行包含两个数 N 和 M，N 表示初始时数列中数的个数，M表示要进行的操作数目。
</p>
<p style="margin-left:0px;">
第 2 行包含 N 个数字，描述初始时的数列。
</p>
<p style="margin-left:0px;">
以下 M 行，每行一条命令，格式参见问题描述中的表格。
</p>
<p style="margin-left:0px;">
【输出格式】
</p>
<p style="margin-left:0px;">
对于输入数据中的 GET-SUM 和 MAX-SUM 操作，向输出文件依次打印结果，每个答案（数字）占一行。
</p>
<p style="margin-left:0px;">
【输入样例】
</p>
<pre>9 8
2 -6 3 5 1 -5 -3 6 3
GET-SUM 5 4
MAX-SUM INSERT 8 3 -5 7 2
DELETE 12 1
MAKE-SAME 3 3 2
REVERSE 3 6
GET-SUM 5 4
MAX-SUM
</pre>
<p style="margin-left:0px;">
【输出样例】
</p>
<pre>-1
10
1
10
</pre>
<p style="margin-left:0px;">
【样例说明】
</p>
<p style="margin-left:0px;">
初始时，我们拥有数列 2 -6 3 5 1 -5 -3 6 3
</p>
<p style="margin-left:0px;">
执行操作 GET-SUM 5 4，表示求出数列中从第 5 个数开始连续 4 个数字之和，1+(-5)+(-3)+6 = -1：
</p>
<pre>2     -6     3      5      1     -5    -3     6      3

</pre>
<p style="margin-left:0px;">
执行操作 MAX-SUM，表示要求求出当前数列中最大的一段和，应为 3+5+1+(-5)+(-3)+6+3 = 10：
</p>
<pre>2     -6     3      5      1     -5    -3     6      3

</pre>
<p style="margin-left:0px;">
执行操作 INSERT 8 3 -5 7 2，即在数列中第 8 个数字后插入-5 7 2，
</p>
<pre>2     -6     3      5      1     -5    -3     6     -5     7      2      3

</pre>
<p style="margin-left:0px;">
执行操作 DELETE 12 1，表示删除第 12 个数字，即最后一个：
</p>
<pre>2     -6     3      5      1     -5    -3     6     -5     7      2

</pre>
<p style="margin-left:0px;">
执行操作 MAKE-SAME 3 3 2，表示从第 3 个数开始的 3 个数字，统一修改为 2：
</p>
<pre>2	-6	3	5	1	-5	-3	6	-5	7	2
</pre>
<p style="margin-left:0px;">
改为
</p>
<pre>2	-6	2	2	2	-5	-3	6	-5	7	2
</pre>
<p style="margin-left:0px;">
执行操作 REVERSE 3 6，表示取出数
</p>
