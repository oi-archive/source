# 

 
 # 题目描述 
<p>
字母排序ALPHA(alpha.pas/c/cpp)

 
 # 输入格式 
<p>
　　输入文件的第一行是两个整数A（<=26）、K(<=500000)，A表示需要恢复的字母的个数，K表示字典里与这几个字母有关系的单词个数。接下来的K行按原来的字典顺序给出这K个单词，第K+1行是要你恢复的字母组，字母为小写字母。</p> 

 
 # 输出格式 
<p>
输出文件应该将字母组输出，如果不可将字母分别，你将输出0。
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
<tr><td>5  6 
cebdbac
cac
ecd
dca
aba
bac
cedab
</td><td>
abcde
</td></tr></table>