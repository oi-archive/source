# 

 
 # 题目描述 
<p>
痛苦的听写（english.pas\c\cpp）<br><br>【题目描述】<br>　　上了高二，换了一个英语老师。这个英语老师一上课就听写单词。听写单词倒没什么，问题是他听写单词只说中文，而作为一个英语国际高标准人才，词汇量当然不少。你只说中文我怎么知道是哪个单词…(学过英语的都知道，同样中文意思有多个英文单词)于是，每次听写单词，xm总是一堆红叉…(其实是一两个而已)每次更正xm都很不爽，于是，他把更正单词这个重任交给了会编程的你…^_^</p> 

 
 # 输入格式 
<p>
　　输入文件english.in一共只有两行。<br>　　第一行为xm默写的单词组成的字符串(长度小于等于1000)。<br>　　第二行为正确单词组成的字符串(长度小于等于1000)。<br></p> 

 
 # 输出格式 
<p>
　　输出文件中english.out输出需要更正的最小总步数，然后接下来每行输出每一步的操作。<br>　　一共有三种基本操作：<br>　　1、删除一个字母(Delete)<br>　　2、插入一个字母(Insert)<br>　　3、将一个字母替换成另一个(Replace)<br></p> 
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
<tr><td>I love u.
I hate you.
</td><td>5
Replace 3,h
Replace 4,a
Replace 5,t
Insert 8,o
Insert 8,y</td></tr></table>
