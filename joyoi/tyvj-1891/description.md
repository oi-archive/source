# 

 
 # 题目描述 
【问题描述】<BR>&nbsp;&nbsp;&nbsp;&nbsp;给出一个长度不超过200的由小写英文字母组成的字母串（约定：该字串以每行20个字母的方式输入，且保证每行一定为20个）。要求将此字母串分成k份（1＜k≤40），且每份中包含的单词个数加起来总数最大（每份中包含的单词可以部分重叠。当选用一个单词之后，其第一个字母不能再用。例如字符串this中可以包含this和is，选用this之后就不能包含t）。在给出的一个不超过6个单词的字典中，要求输出最大的单词个数。 

 
 # 输入格式 
&nbsp;第一行有二个正整数：（p，k），其中p表示字串的行数；k表示分为k个部分。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来的p行，每行均有20个字符。<BR>&nbsp;&nbsp;&nbsp;&nbsp;再接下来有一个正整数s，表示字典中单词个数。（l≤s≤6）<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来的s行，每行均有一个单词。 

 
 # 输出格式 
&nbsp;结果输出至屏幕，每行一个整数，分别对应每组测试数据的相应结果。 
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
<tr><td>1 3
thisisabookyouareaoh
4
is
a
ok
sab
</td><td>7</td></tr></table>
