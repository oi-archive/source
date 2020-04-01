# 

 
 # 题目描述 
<p align="left" style="margin-left:27.0pt;">Tom写了一封信，为了防止被偷看，他设计了一个加密函数。&nbsp;我们可以认为信是一个字符串&nbsp;W，设&nbsp;phi（W）为加密后的字符串：</p>

<p align="left" style="margin-left:45.0pt;">1、&nbsp;如果&nbsp;W&nbsp;的长度为&nbsp;1，那么&nbsp;phi(W)=W；</p>

<p align="left" style="margin-left:45.0pt;">2、&nbsp;设&nbsp;W=w1w2&hellip;wN，令&nbsp;K=N&nbsp;div&nbsp;2（下取整）；</p>

<p align="left" style="margin-left:27.0pt;">3、&nbsp;phi(W)&nbsp;=&nbsp;phi(wNwN-1...wK+1)&nbsp;+&nbsp;phi(wKwK-1...w1)。&nbsp;举个例子，phi(&lsquo;Ok&rsquo;)&nbsp;=&nbsp;&lsquo;kO&rsquo;，phi(&lsquo;abcd&rsquo;)&nbsp;=&nbsp;&lsquo;cdab&rsquo;。</p>

<p align="left" style="margin-left:6.0pt;">现在小&nbsp;y&nbsp;截获了Tom信，他想破译这封信。但是由于他太忙，现在他&nbsp;交给你这个任务，询问原字符串的第&nbsp;q&nbsp;个字符在加密后的字符串中的位置。</p> 

 
 # 输入格式 
<p>输入一行两个整数&nbsp;N,&nbsp;q&nbsp;(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10^9；1&nbsp;&lt;=&nbsp;q&nbsp;&lt;=&nbsp;N)。</p> 

 
 # 输出格式 
<p>输出一行一个整数，表示第&nbsp;q&nbsp;个字符加密后的位置。</p> 
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
<tr><td>9 4</td><td>8</td></tr></table>
