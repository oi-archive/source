# 

 
 # 题目描述 
我们定义字符串A是字符串B的子串当且仅当我们能在B串中找到A串。现在给你一个字符串A，和另外一个字符串B，要你每次从B串中从左至右找第一个A串，并从B串中删除它，直到A串不为B串的子串，问你需要进行几次删除操作。 

 
 # 输入格式 
输入文件共2行，第一行一个字符串A（长度小于256），第二行一个字符串B。<BR>&nbsp;&nbsp;&nbsp;&nbsp;30%的数据是随机生成的；<BR>&nbsp;&nbsp;&nbsp;&nbsp;50%的数据满足输入文件大小小于300KB；<BR>&nbsp;&nbsp;&nbsp;&nbsp;100%的数据满足输入文件小于500KB，字符串A、B中只会出现英文字母。<BR> 

 
 # 输出格式 
输出文件只有一个整数N。 

 
 # 提示 
样例说明:abcabcabaabcbccc-&gt;&nbsp;abcabaabcbccc-&gt;&nbsp;abaabcbccc-&gt;&nbsp;ababccc-&gt;&nbsp;abccConan&nbsp;From&nbsp;lsq 
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
<tr><td>abc
abcabcabaabcbccc
</td><td>5
</td></tr></table>
