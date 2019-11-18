# 

 
 # 题目背景 
2007年江苏省省选第一试 

 
 # 题目描述 
将哈夫曼编码中的0、1编码方案，推广到0、1、2、..&nbsp;&nbsp;p&nbsp;，要求使输入的字符串编码长度最小。<BR>&nbsp;&nbsp;&nbsp;例如：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入字符串&nbsp;&nbsp;ˋa&nbsp;b&nbsp;c&nbsp;d&nbsp;a&nbsp;b&nbsp;c&nbsp;a&nbsp;b&nbsp;a&nbsp;aˊ和&nbsp;p=2<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有编码方案：&nbsp;&nbsp;a&nbsp;______&nbsp;0<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b&nbsp;______&nbsp;1<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c&nbsp;______&nbsp;20<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d&nbsp;______&nbsp;21<BR>此时，该字符串的编码长度为14&nbsp;(编码方法不唯一，但总长度最小值唯一)<BR> 

 
 # 输入格式 
　第一行一个整数p&nbsp;&nbsp;(1≤p≤9)<BR>&nbsp;第二行为一个字符串（全是由小写字母组成，长度≤100）<BR> 

 
 # 输出格式 
输出一个数（满足条件的编码长度最小值） 

 
 # 提示 
2007年江苏省省选第一试 
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
<tr><td>2    
abcdabcabaa
</td><td>14</td></tr></table>
