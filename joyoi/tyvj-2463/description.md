# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
*第一行：三个由空格隔开的整数：s1,s2,s3

 
 # 输出格式 
<p>

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
<tr><td>3 2 3

</td><td>5


输出详解:


这里是所有可能的情况.

1 1 1 -> 3 1 2 1 -> 4 2 1 1 -> 4 2 2 1 -> 5 3 1 1 -> 5 3 2 1 -> 6

1 1 2 -> 4 1 2 2 -> 5 2 1 2 -> 5 2 2 2 -> 6 3 1 2 -> 6 3 2 2 -> 7

1 1 3 -> 5 1 2 3 -> 6 2 1 3 -> 6 2 2 3 -> 7 3 1 3 -> 7 3 2 3 -> 8

5和6出现的几率都是最大的，所以输出5.