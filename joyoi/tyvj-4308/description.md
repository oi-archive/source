# 

 
 # 题目描述 
<p>　　给定一个文章和一个单词，请编写一个程序，输出它在给定的文章中出现的次数和第一次出现的位置。</p>

<p>　　注意：匹配单词时，不区分大小写，但要求完全匹配，即给定单词必须与文章中的某一独立单词在不区分大小写的情况下完全相同（参见样例1），如果给定单词仅是文章中某一单词的一部分则不算匹配（参见样例2）。</p> 

 
 # 输入格式 
<p align="left">用标准输入来输入数据。输入共2行。</p>

<p align="left">第&nbsp;1&nbsp;行为一个字符串，其中只含字母，表示给定单词。</p>

<p align="left">第&nbsp;2&nbsp;行为一个字符串，其中只可能包含字母和空格，表示给定的文章。</p> 

 
 # 输出格式 
<p>　　用标准输出来输出答案。只有一行，如果在文章中找到给定单词则输出两个整数，两个整数之间用一个空格隔开，分别是单词在文章中出现的次数和第一次出现的位置（即在文章中第一次出现时，单词首字母在文章中的位置，位置从0&nbsp;开始）；如果单词在文章中没有出现，则直接输出一个整数-1。</p> 

 
 # 提示 
<p align="left">【注意】</p>

<p align="left">关于测试数据第一行：按理来说最后的字母后面是没有空格的，但网页会自动在最后加上空格。自己测试的时候可以手动删掉。</p>

<p align="left">&nbsp;</p>

<p align="left">【输入输出样例&nbsp;1&nbsp;说明】</p>

<p align="left">输出结果表示给定的单词&nbsp;To&nbsp;在文章中出现两次，第一次出现的位置为0。</p>

<p align="left">&nbsp;</p>

<p align="left">【输入输出样例&nbsp;2&nbsp;说明】</p>

<p align="left">表示给定的单词&nbsp;to&nbsp;在文章中没有出现，输出整数-1。</p>

<p align="left">&nbsp;</p>

<p align="left">【数据范围】</p>

<p align="left">1&lt;=单词长度&lt;=10。</p>

<p align="left">1&lt;=文章长度&lt;=1,000,000。</p> 
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
<tr><td>To
to be or not to be is a question</td><td>2 0
</td></tr><tr><td>to
Did the Ottoman Empire lose its power at that time
</td><td>-1
</td></tr></table>
