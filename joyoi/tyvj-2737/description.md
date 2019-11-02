# 

 
 # 题目描述 
<p>
    从一个给定的串中删去（不一定连续地删去）0个或0个以上的字符，剩下的字符按原来的顺序组成的串是该串的子串。例如：””,”a”,”xb”,”aaa”,”bbb”,”xabbb”,”xaaabbb”都是串“xaaabbb”的子串（例子中的串不包含引号）。<br>编程求N个非空串的最长公共子串的长度。限制：N大于等于2小于等于100;N个串中的字符只会是数字0，1，…，9或小写英文字符a,b,…,z；每个串非空且最多含100个字符；N个串的长度的乘积不会超过30000。<br></p> 

 
 # 输入格式 
<p>
文件第一行是一个整数T，表示测试数据的个数N大于等于1小于等于10。接下来有T组测试数据。各组测试数据的第一行是一个整数Ni。表示第i组数据中串的个数。各组测试数据的第2到N+1行中，每行一个串，串中不会有空格，但行首和行末可能有空格，这些空格当然不算作串的一部分。</p> 

 
 # 输出格式 
<p>
输出T行，每行一个数，第i行的数表示第i组测试数据中Ni个非空串的最长公共子串的长度。</p> 
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
<tr><td>1
3
ab
bc
cd
</td><td>0</td></tr></table>
