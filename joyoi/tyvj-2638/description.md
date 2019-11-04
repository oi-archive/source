# 

 
 # 题目描述 
<p>
人们在英文字典中查找某个单词的时候可能不知道该单词的完整拼法，而只知道该单词的一个错误的近似拼法，这时人们可能陷入困境，为了查找一个单词而浪费大量的时间。带有模糊查询功能的电子字典能够从一定程度上解决这一问题：用户只要输入一个字符串，电子字典就返回与该单词编辑距离最小的几个单词供用户选择。

 
 # 输入格式 
<p>
第一行包含两个正整数N (N  < =  10,000)和M (M < = 10,000)。

 
 # 输出格式 
<p>
输出应包括M行，第i行为一个整数Xi。Xi = -1表示Qi为字典中的单词；否则Xi表示与Qi编辑距离为1的单词的个数。

 
 # 提示 
<p>
abcd在单词表中出现过；abc与单词abcd、aabc的编辑距离都是1；abcdd与单词abcd、abcde、abced的编辑距离都是1。
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
<tr><td>4 3
abcd
abcde
aabc
abced
abcd
abc
abcdd	</td><td>-1
2
3
