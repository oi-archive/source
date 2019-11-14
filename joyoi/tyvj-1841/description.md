# 

 
 # 题目背景 
JSOI2009第二轮一试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;人们在英文字典中查找某个单词的时候可能不知道该单词的完整拼法，而只知道该单词的一个错误的近似拼法，这时人们可能陷入困境，为了查找一个单词而浪费大量的时间。带有模糊查询功能的电子字典能够从一定程度上解决这一问题：用户只要输入一个字符串，电子字典就返回与该单词编辑距离最小的几个单词供用户选择。&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;字符串a与字符串b的编辑距离是指：允许对a或b串进行下列“编辑”操作，将a变为b或b变为a，最少“编辑”次数即为距离。<BR>&nbsp;&nbsp;&nbsp;&nbsp;1.删除串中某个位置的字母；<BR>&nbsp;&nbsp;&nbsp;&nbsp;2.添加一个字母到串中某个位置；<BR>&nbsp;&nbsp;&nbsp;&nbsp;3.替换串中某一位置的一个字母为另一个字母；<BR>&nbsp;&nbsp;&nbsp;&nbsp;JSOI团队正在开发一款电子字典，你需要帮助团队实现一个用于模糊查询功能的计数部件：对于一个待查询字符串，如果它是单词，则返回-1；如果它不是单词，则返回字典中有多少个单词与它的编辑距离为1。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件wordquery.in的第一行包含两个正整数N&nbsp;(N&nbsp;≤&nbsp;10,000)和M&nbsp;(M&nbsp;≤&nbsp;10,000)。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来的N行，每行一个字符串，第i&nbsp;+&nbsp;1行为单词Wi。单词长度在1至20之间。再接下来M行，每行一个字符串，第i&nbsp;+&nbsp;N&nbsp;+&nbsp;1表示一个待查字符串Qi。待查字符串长度在1至20之间。Wi和Qi均由小写字母构成，文件中不包含多余空格。所有单词互不相同，但是查询字符串可能有重复。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;请将输出写至文件wordquery.out。输出应包括M行，第i行为一个整数Xi。Xi&nbsp;=&nbsp;-1表示Qi为字典中的单词；否则Xi表示与Qi编辑距离为1的单词的个数。 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;abcd在单词表中出现过；abc与单词abcd、aabc的编辑距离都是1；abcdd与单词abcd、abcde、abced的编辑距离都是1。<BR>&nbsp;&nbsp;&nbsp;&nbsp;对50%的数据范围：N&lt;=1,000，M&lt;=1,000<BR>&nbsp;&nbsp;&nbsp;&nbsp;对100%的数据范围：N&lt;=10,000,&nbsp;M&lt;=10,000 
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
abcdd
</td><td>-1
2
3
</td></tr></table>
