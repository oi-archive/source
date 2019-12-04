# 

 
 # 题目描述 
<p>
给出n个回文串s1, s2, …, sn <br>求如下二元组(i, j)的个数 <br>si + sj 仍然是回文串 <br><br>规模 <br>输入串总长不超过2M bytes <br><br><br></p> 

 
 # 输入格式 
<p>
The first line of input file contains the number of strings n. The following n lines describe each string: <br>The i+1-th line contains the length of the i-th string li, then a single space and a string of li small letters of English alphabet. <br><br>You can assume that the total length of all strings will not exceed 2,000,000. Two strings in different line may be the same. <br></p> 

 
 # 输出格式 
<p>
Print out only one integer, the number of palindromes</p> 
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
<tr><td>6 
2 aa 
3 aba 
3 aaa 
6 abaaba 
5 aaaaa 
4 abba

</td><td>14</td></tr></table>
