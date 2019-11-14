# 

 
 # 题目描述 
<p>在有道搜索框中，当输入一个或者多个字符时，搜索框会出现一定数量的提示，如下图所示：<br />
<img align="middle" border="0" src="/source/joyoi/tyvj-1228/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIyOC9odHRwOi8vd3d3LnR5dmouY246ODA4MC9Qcm9ibGVtSW1nLzEyMjguanBn.jpg" /><br />
现在给你N个单词和一些查询，请输出提示结果，为了简这个问题，只需要输出以查询词为前缀的并且按字典序排列的最前面的8个单词，如果符合要求的单词一个也没有请只输出当前查询词。&nbsp;</p> 

 
 # 输入格式 
<p>第一行是一个正整数N，表示词表中有N个单词。<br />
接下来有N行，每行都有一个单词，注意词表中的单词可能有重复，请忽略掉重复单词。所有的单词都由小写字母组成。<br />
接下来的一行有一个正整数Q，表示接下来有Q个查询。<br />
接下来Q行，每行有一个单词，表示一个查询词，所有的查询词也都是由小写字母组成，并且所有的单词以及查询的长度都不超过20，且都不为空<br />
其中：N&lt;=10000,Q&lt;=10000&nbsp;</p> 

 
 # 输出格式 
<p>对于每个查询，输出一行，按顺序输出该查询词的提示结果，用空格隔开。&nbsp;</p> 
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
<tr><td>10
a
ab
hello
that
those
dict
youdao
world
your
dictionary
6
bob
d
dict
dicti
yo
z</td><td>bob
dict dictionary
dict dictionary
dictionary
youdao your
z
</td></tr></table>
