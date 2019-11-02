# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;设有N堆沙子排成一排，其编号为1，2，3，…，N（N&lt;=300）。每堆沙子有一定的数量，可以用一个整数来描述，现在要将这N堆沙子合并成为一堆，每次只能合并相邻的两堆，合并的代价为这两堆沙子的数量之和，合并后与这两堆沙子相邻的沙子将和新堆相邻，合并时由于选择的顺序不同，合并的总代价也不相同，如有4堆沙子分别为&nbsp;1&nbsp;&nbsp;3&nbsp;&nbsp;5&nbsp;&nbsp;2&nbsp;我们可以先合并1、2堆，代价为4，得到4&nbsp;5&nbsp;2&nbsp;又合并&nbsp;1，2堆，代价为9，得到9&nbsp;2&nbsp;，再合并得到11，总代价为4+9+11=24，如果第二步是先合并2，3堆，则代价为7，得到4&nbsp;7，最后一次合并代价为11，总代价为4+7+11=22；问题是：找出一种合理的方法，使总的代价最小。输出最小代价。 

 
 # 输入格式 
第一行一个数N表示沙子的堆数N。<BR>第二行N个数，表示每堆沙子的质量。&nbsp;&lt;=1000 

 
 # 输出格式 
合并的最小代价 
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
<tr><td>4
1 3 5 2</td><td>22</td></tr></table>
