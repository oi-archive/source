# 

 
 # 题目背景 
NOIP2008复赛提高组第一题<BR> 

 
 # 题目描述 
笨小猴的词汇量很小，所以每次做英语选择题的时候都很头疼。但是他找到了一种方法，经试验证明，用这种方法去选择选项的时候选对的几率非常大！<BR>这种方法的具体描述如下：假设maxn是单词中出现次数最多的字母的出现次数，minn是单词中出现次数最少的字母的出现次数，如果maxn-minn是一个质数，那么笨小猴就认为这是个Lucky&nbsp;Word，这样的单词很可能就是正确的答案。<BR> 

 
 # 输入格式 
输入只有一行，是一个单词，其中只可能出现小写字母，并且长度小于100。 

 
 # 输出格式 
输出共两行，第一行是一个字符串，假设输入的的单词是Lucky&nbsp;Word，那么输出“Lucky&nbsp;Word”，否则输出“No&nbsp;Answer”；<BR>第二行是一个整数，如果输入单词是Lucky&nbsp;Word，输出maxn-minn的值，否则输出0。<BR> 
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
<tr><td>输入样例1
error

输入样例2
olympic
</td><td>输出样例1
Lucky Word
2

输出样例2
No Answer
0
</td></tr></table>
