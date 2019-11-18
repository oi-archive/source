# 
描述：给定n*n由0和1组成的矩阵，如果矩阵的每一行和每一列的1的数量都是偶数，则认为符合条件。 
你的任务就是检测矩阵是否符合条件，或者在仅改变一个矩阵元素的情况下能否符合条件。 
"改变矩阵元素"的操作定义为0变成1或者1变成0。

输入：输入n + 1行，第1行为矩阵的大小n(0 < n < 100)，以下n行为矩阵的每一行的元素，元素之间以一个空格分开。

输出：如果矩阵符合条件，则输出OK；
如果矩阵仅改变一个矩阵元素就能符合条件，则输出需要改变的元素所在的行号和列号，以一个空格分开。
如果不符合以上两条，输出Corrupt。# 样例数据
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
1 0 1 0
0 0 0 0
1 1 1 1
0 1 0 1</td><td>OK</td></tr><tr><td>4
1 0 1 0
0 0 1 0
1 1 1 1
0 1 0 1</td><td>2 3</td></tr><tr><td>4
1 0 1 0
0 1 1 0
1 1 1 1
0 1 0 1</td><td>Corrupt</td></tr></table>
