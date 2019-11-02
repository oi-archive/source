# 

 
 # 题目描述 
请写一个程序，要求维护一个数列，支持以下6种操作：（请注意，格式栏中的下划线‘&nbsp;_&nbsp;’表示实际输入文件中的空格）<BR>操作编号&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入文件中的格式&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;说明<BR>1.&nbsp;插入&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;INSERT_posi_tot_c1_c2_..._ctot&nbsp;&nbsp;&nbsp;在当前数列的第posi个数字后插入tot个数字：c1,&nbsp;c2,&nbsp;…,&nbsp;ctot；若在数列首插入，则posi为0<BR>2.&nbsp;删除&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DELETE_posi_tot&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;从当前数列的第posi个数字开始连续删除tot个数字<BR>3.&nbsp;修改&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MAKE-SAME_posi_tot_c&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;将当前数列的第posi个数字开始的连续tot个数字统一修改为c<BR>4.&nbsp;翻转&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;REVERSE_posi_tot&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;取出从当前数列的第posi个数字开始的tot个数字，翻转后放入原来的位置<BR>5.&nbsp;求和&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GET-SUM_posi_tot&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;计算从当前数列开始的第posi个数字开始的tot个数字的和并输出<BR>6.&nbsp;求和最大的子列&nbsp;&nbsp;&nbsp;&nbsp;MAX-SUM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;求出当前数列中和最大的一段子列，并输出最大和<BR> 

 
 # 输入格式 
输入文件的第&nbsp;1&nbsp;行包含两个数N&nbsp;和M，N&nbsp;表示初始时数列中数的个数，M<BR>表示要进行的操作数目。<BR>第2行包含N个数字，描述初始时的数列。<BR>以下M行，每行一条命令，格式参见问题描述中的表格。 

 
 # 输出格式 
对于输入数据中的GET-SUM&nbsp;和MAX-SUM&nbsp;操作，向输出文件依次打印结<BR>果，每个答案（数字）占一行。 

 
 # 提示 
【样例说明】<BR>初始时，我们拥有数列<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;3&nbsp;<BR>执行操作GET-SUM&nbsp;5&nbsp;4，表示求出数列中从第5个数开始连续4个数字之和，如下图中的灰色部分1+(-5)+(-3)+6&nbsp;=&nbsp;-1：<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;3&nbsp;<BR>执行操作MAX-SUM，表示要求求出当前数列中最大的一段和，即如下图所示，应为3+5+1+(-5)+(-3)+6+3&nbsp;=&nbsp;10：<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;&nbsp;3&nbsp;<BR>执行操作INSERT&nbsp;8&nbsp;3&nbsp;-5&nbsp;7&nbsp;2，即在数列中第8个数字后插入-5&nbsp;7&nbsp;2，如下所示的灰色部分：<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;3&nbsp;<BR>执行操作DELETE&nbsp;12&nbsp;1，表示删除第12个数字，即最后一个：<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;3<BR>执行操作MAKE-SAME&nbsp;3&nbsp;3&nbsp;2，表示从第3个数开始的3个数字，即下图中的灰色部分，统一修改为2：<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;<BR>改为<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;<BR>执行操作REVERSE&nbsp;3&nbsp;6，表示取出数列中从第3个数开始的连续6个数：&nbsp;<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;-5&nbsp;&nbsp;-3&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;<BR>如上所示的灰色部分2&nbsp;2&nbsp;2&nbsp;-5&nbsp;-3&nbsp;6，翻转后得到6&nbsp;-3&nbsp;-5&nbsp;2&nbsp;2&nbsp;2，并放回原来位置：<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-3&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;<BR>最后执行GET-SUM&nbsp;5&nbsp;4和MAX-SUM，不难得到答案1和10。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/~&nbsp;GET-SUM&nbsp;~\<BR>2&nbsp;&nbsp;-6&nbsp;&nbsp;&nbsp;6&nbsp;&nbsp;-3&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;-5&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;2&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\____&nbsp;MAX-SUM&nbsp;______/<BR><BR><BR>你可以认为在任何时刻，数列中至少有1个数。<BR>输入数据一定是正确的，即指定位置的数在数列中一定存在。<BR>50%的数据中，任何时刻数列中最多含有30&nbsp;000个数；<BR>100%的数据中，任何时刻数列中最多含有500&nbsp;000个数。<BR>100%的数据中，任何时刻数列中任何一个数字均在[-1&nbsp;000,&nbsp;1&nbsp;000]内。<BR>100%的数据中，M&nbsp;≤20&nbsp;000，插入的数字总数不超过4&nbsp;000&nbsp;000个，输入文件<BR>大小不超过20MBytes。 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>9 8
2 -6 3 5 1 -5 -3 6 3
GET-SUM 5 4
MAX-SUM
INSERT 8 3 -5 7 2
DELETE 12 1
MAKE-SAME 3 3 2
REVERSE 3 6
GET-SUM 5 4
MAX-SUM</td><td>-1
10
1
10</td></tr></table>
