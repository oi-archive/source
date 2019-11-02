# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;有n个木块排成一行，从左到右依次编号为1~n。你有&nbsp;k种颜色的油漆，其<BR>中第&nbsp;i&nbsp;种颜色的油漆足够涂&nbsp;ci&nbsp;个木块。所有油漆刚好足够涂满所有木块，即<BR>c1+c2+...+ck=n。相邻两个木块涂相同色显得很难看，所以你希望统计任意两个相<BR>邻木块颜色不同的着色方案。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;第一行为一个正整数k，第二行包含&nbsp;k个整数c1,&nbsp;c2,&nbsp;...&nbsp;,&nbsp;ck。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出一个整数，即方案总数模1,000,000,007的结果。 

 
 # 提示 
【数据规模】&nbsp;<BR>50%的数据满足：1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;5,&nbsp;1&nbsp;&lt;=&nbsp;ci&nbsp;&lt;=&nbsp;3&nbsp;<BR>100%的数据满足：1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;15,&nbsp;1&nbsp;&lt;=&nbsp;ci&nbsp;&lt;=&nbsp;5SCOI2008&nbsp;day2&nbsp;t1 
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
<tr><td>样例1：

3 
1 2 3

样例2：
5 
2 2 2 2 2

样例3：

10 
1 1 2 2 3 3 4 4 5 5</td><td>样例1：

10 

样例2：

39480

样例3：

85937576</td></tr></table>
