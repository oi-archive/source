# 

 
 # 题目描述 
我们定义一个字符串的后缀suffix(i)表示从s[i]到s[length(s)]这段子串。<BR>后缀数组（Suffix&nbsp;array）SA[i]中存放着一个排列，满足suffix(sa[i])&lt;suffix(sa[i+1])&nbsp;按照字典序方式比较<BR>定义height[i]表示suffix(sa[i])与suffix(sa[i-1])之间的最长公共前缀长度，其中height[1]=0<BR>你的任务就是求出SA和height这两个数组。字符串长度&lt;=200000 

 
 # 输入格式 
一行，为描述中的字符串（仅会出现小写字母） 

 
 # 输出格式 
共两行，每行n个数，第一行为sa[i]，第二行为height[i]，其中每行的数均用空格隔开 
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
<tr><td>aabaaaab
</td><td>4 5 6 1 7 2 8 3
0 3 2 3 1 2 0 1</td></tr></table>
