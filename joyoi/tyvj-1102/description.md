# 

 
 # 题目描述 
有一个很长的由小写字母组成字符串。为了便于对这个字符串进行分析，需要将它划分成若干个部分，每个部分称为一个单词。出于减少分析量的目的，我们希望划分出的单词数越少越好。你就是来完成这一划分工作的。 

 
 # 输入格式 
第一行，一个字符串。（字符串的长度不超过100）<BR>第二行一个整数n，表示单词的个数。（n&lt;=100）<BR>第3~n+2行，每行列出一个单词。<BR> 

 
 # 输出格式 
一个整数，表示字符串可以被划分成的最少的单词数。 

 
 # 提示 
（原字符串可拆成real+it+your或reality+our，由于reality+our仅为两个部分，因此最优解为2，另外注意，单词列表中的每个单词都可以重复使用多次，也可以不用） 
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
<tr><td>realityour
5
real
reality
it
your
our
</td><td>2
</td></tr></table>
