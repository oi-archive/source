# 

 
 # 题目描述 
给定一个信封，最多只允许粘贴N（N≤100）张邮票，我们现在有M（M≤100）种邮票，面值分别为：X1，X2……Xm（Xi≤255为正整数），并假设各种邮票都有足够多张。<BR>要求计算所能获得的邮资最大范围。即求最大值MAX，使1-MAX之间的每一个邮资都能得到。<BR>例如：N=4，有2种邮票，面值分别为1分，4分，于是可以得到1-10分和12分，13分，16分邮资，由于得不到11分和15分，所以邮资的最大范围max=10 

 
 # 输入格式 
第一行为最多粘贴的邮票张数n。第二行为邮票种数m。以下m行各有一个数字表示邮票的面值。 

 
 # 输出格式 
仅一个数，最大的max的值。 
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
2
1
4
</td><td>10</td></tr></table>
