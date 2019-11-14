# 

 
 # 题目背景 
NOIP2011普及组第二题 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;一般的文本编辑器都有查找单词的功能，该功能可以快速定位特定单词在文章中的位置，有的还能统计出特定单词在文章中出现的次数。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，请你编程实现这一功能，具体要求是：给定一个单词，请你输出它在给定的文章中出现的次数和第一次出现的位置。!!注意：匹配单词时，不区分大小写，但要求完全匹配，即给定单词必须与文章中的某一独立单词在不区分大小写的情况下完全相同（参见样例&nbsp;1），如果给定单词仅是文章中某一单词的一部分则不算匹配（参见样例&nbsp;2）。&nbsp;<BR> 

 
 # 输入格式 
第&nbsp;1&nbsp;行为一个字符串，其中只含字母，表示给定单词；&nbsp;<BR>第&nbsp;2&nbsp;行为一个字符串，其中只可能包含字母和空格，表示给定的文章。&nbsp; 

 
 # 输出格式 
只有一行，如果在文章中找到给定单词则输出两个整数，两个整数之间用一个空格隔开，分别是单词在文章中出现的次数和第一次出现的位置（即在文章中第一次出现时，单词首字母在文章中的位置，位置从&nbsp;0&nbsp;开始）；如果单词在文章中没有出现，则直接输出一个整数-1。&nbsp; 

 
 # 提示 
1≤单词长度≤10。&nbsp;<BR>1≤文章长度≤1,000,000。&nbsp; 
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
<tr><td>input1
To 
to be or not to be is a question

input2
to 
Did the Ottoman Empire lose its power at that time
 </td><td>output1
2 0

output2
-1

【输入输出样例 2 说明】 
表示给定的单词 to 在文章中没有出现，输出整数-1。 </td></tr></table>
