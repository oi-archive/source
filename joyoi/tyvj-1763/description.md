# 

 
 # 题目描述 
【问题描述】：	给一个数字串s和正整数d,&nbsp;统计s有多少种不同的排列能被d整除（可以有前导0）。例如123434有90种排列能被2整除，其中末位为2的有30种，末位为4的有60种。 

 
 # 输入格式 
【输入】<BR>&nbsp;&nbsp;	输入第一行是一个整数T，表示测试数据的个数，以下每行一组s和d，中间用空格隔开。s保证只包含数字0,&nbsp;1,&nbsp;2,&nbsp;3,&nbsp;4,&nbsp;5,&nbsp;6,&nbsp;7,&nbsp;8,&nbsp;9. 

 
 # 输出格式 
【输出】<BR>&nbsp;&nbsp;&nbsp;每个数据仅一行，表示能被d整除的排列的个数。 

 
 # 提示 
【样例说明】<BR>在前三个例子中，排列分别有1,&nbsp;3,&nbsp;3628800种，它们都是1的倍数。<BR><BR>【限制】<BR>20%的数据满足：s的长度不超过5,&nbsp;1&lt;=T&lt;=5<BR>50%的数据满足：s的长度不超过8<BR>100%的数据满足：s的长度不超过10,&nbsp;1&lt;=d&lt;=1000,&nbsp;1&lt;=T&lt;=15,<BR> 
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
<tr><td>【样例输入】
7
000 1
001 1
1234567890 1
123434 2
1234 7
12345 17
12345678 29</td><td>【样例输出】
1</td></tr></table>
