# 

 
 # 题目描述 
<p>
单词背诵（letter.pas\c\cpp）<br><br>【题目描述】<br>　　小小在背单词，她发现当背诵了单词beauty 以后 ，再接着背诵单词beautiful 就会觉得容易许多。由于有很多单词要背，她希望找到一种好的背诵顺序。单词A和它的前驱B的最大公共前缀的长度称为背诵单词A的便利值(例如：B=’beauty’,A=’beautiful’,则A的便利值是len({A,B})=len(’beaut’)=5),我们认为一个背诵单词A的花费是它的长度(例如:’beautiful’的长度len(‘beautiful’)=9)与它的便利值之差（对于上述例子背诵A的花费为9-5=4）。请你求一个背诵顺序，使得背诵这些单词的花费总和最小。假设一开始你什么单词都不记得。</p> 

 
 # 输入格式 
<p>
　　输入文件letter.in给定一个单词表：第一行N（N < 100）表示单词总数。接下来N行，每行一个单词。每个单词的长度不超过20，均为小写字母组成。</p> 

 
 # 输出格式 
<p>
　　输出文件letter.out按照背诵顺序输出每个单词，每个单词占一行，不能有多余的字符。<br></p> 
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
<tr><td>5
beauty
beautiful
flower
man
dog 
</td><td>beauty
beautiful
dog
flower
man</td></tr></table>
