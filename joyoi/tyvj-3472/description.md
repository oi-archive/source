# 

 
 # 题目描述 
<p>
字母排序ALPHA(alpha.pas/c/cpp)<br><br>【问题描述】<br><br>　　G教授是XOI的负责人，有一天他竟然发现自己的计算机染上了一种不常见的病毒这种病毒的名字叫做ALPHABETVIRUS，当它发作的时候，它会将字母用其它的字母代替，但它不会将单词的顺序交换。<br>　　病毒将计算机中的所有文档都作了相对应的改变，很幸运，G教授的计算机上有一个字典，而我们都知道字典单词是按字母顺序排列的，当然，这个字典也被病毒改变了。因此，要利用字典原来的有序性，找到病毒替换字母的规律，再用以恢复其它文档。由于XOI是不可缺少G的文件的，所以文档必须恢复。但是由于G教授有其它的更重要工作要完成，所以他希望你可以帮助他恢复文档，使得XOI的工作可以继续。<br>　　G教授会提供感染病毒后的字典和他希望帮助恢复的字母组。<br></p> 

 
 # 输入格式 
<p>
　　输入文件的第一行是两个整数A（<=26）、K(<=500000)，A表示需要恢复的字母的个数，K表示字典里与这几个字母有关系的单词个数。接下来的K行按原来的字典顺序给出这K个单词，第K+1行是要你恢复的字母组，字母为小写字母。</p> 

 
 # 输出格式 
<p>
输出文件应该将字母组输出，如果不可将字母分别，你将输出0。<br>输入输出样例：<br></p> 
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
