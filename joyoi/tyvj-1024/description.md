# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;XXXX年突然有外星人造访，但大家语言不通，不过科学家们经过研究发现外星人用26个英文字母组成的单词中最长不降子序列的长度来表述数字，且英文字母的排列顺序不同，现给出其排列顺序，再给出外星人说的每个数字（其实是每个英文单词，用空格隔开），翻译出外星人所说的数字（连续输出，最后加回车）。<BR>&nbsp;(因为是最长不降子序列，所以数字中没有0，也就是说外星人的数字是&gt;=1的数字)<BR>例如<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我们正常的字母排列顺序是abcdefg…….xyz，代表a&lt;b&lt;c&lt;…..&lt;x&lt;y&lt;z<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;abcd&nbsp;efg&nbsp;hhh&nbsp;ihg四个字符串的最长不降子序列的长度分别为4&nbsp;3&nbsp;3&nbsp;1<BR> 

 
 # 输入格式 
第1，2行为字符串<BR>含义如题描述 

 
 # 输出格式 
输出答案<BR>含义如题描述 

 
 # 提示 
1&lt;=第二行长度&lt;=255<BR><BR><BR>该题被某人形容为恶心。。。。<BR>其实也不是很难做吧？感谢！<BR>zzy 
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
<tr><td>abcdefghijklmnopqrstuvwxyz
abcd efg hhh ihg
</td><td>4331</td></tr></table>
