# 

 
 # 题目描述 
假设有来自&nbsp;n&nbsp;个不同单位的代表参加一次国际会议。每个单位的代表数分别为<BR>ri,&nbsp;i=1,2,...,n。会议餐厅共有&nbsp;m张餐桌，每张餐桌可容纳&nbsp;ci(i=1,2,...,m)&nbsp;个代表就餐。<BR>为了使代表们充分交流，&nbsp;希望从同一个单位来的代表不在同一个餐桌就餐。&nbsp;试设计一个算法，<BR>给出满足要求的代表就餐方案。&nbsp;<BR>&nbsp;<BR>编程任务：&nbsp;<BR>对于给定的代表数和餐桌数以及餐桌容量，编程计算满足要求的代表就餐方案。&nbsp;<BR> 

 
 # 输入格式 
第1行有&nbsp;2&nbsp;个正整数m和&nbsp;n，m表示单位数，n表<BR>示餐桌数，1&lt;=m&lt;=150,&nbsp;1&lt;=n&lt;=270。文件第&nbsp;2&nbsp;行有m个正整数，分别表示每个单位的代表<BR>数。文件第3行有n个正整数，分别表示每个餐桌的容量。<BR> 

 
 # 输出格式 
程序运行结束时，将代表就餐方案输出。如果问题有解，在文件第<BR>1行输出1，否则输出0。接下来的m行给出每个单位代表的就餐桌号。如果有多个满足要<BR>求的方案，只要输出1个方案。<BR> 

 
 # 提示 
各个测试点1s<BR> 
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
<tr><td>4 5 
4 5 3 5 
3 5 2 6 4 
</td><td>1
1 2 4 5
1 2 3 4 5
2 4 5
1 2 3 4 5
</td></tr></table>
