# 

 
 # 题目描述 
<p>
一个词是由至少1个、至多75个小写英文字母组成的。当在一张1个或多个词组成的表中，每一个词(除第一个)都能由在其前一个词的词尾添加1个或多个字母而得到的话，则称此表为一个词链。 <br>例如下面的表： <br>i <br>in <br>int <br>integer <br>为一个含四个词的链,而表： <br>input <br>integer <br>不是链。 <br>一个链的长度是指该链所含词的个数。含一个词的表也是链，其长度为1。 <br><br><br></p> 

 
 # 输入格式 
<p>
你将从输入文件中读到一张表，文件以“.”结束。每行含一个词，表中至少有1个词,而所有词所含字母个数之总和不超过2 000 000个。文件中各行已按字典顺序由小到大排序，且文件中的词不会有重复。<br><br></p> 

 
 # 输出格式 
<p>
你的程序应从输入文件中找出最长的链，并把该链写入到输出文件中。 <br>要求一个词占一行。 <br>若有多个最长链，只须输出其中任何一个。</p> 
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
<tr><td>下面给出了一个由7个词的输入文件和一个对应的输出文件。输入文件中有一个长度为4的链，这里已没有比它更长的链了。
i
if 
in
input
int
integer
output
.

</td><td>i
in
int
integer
</td></tr></table>
