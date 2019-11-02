# 

 
 # 题目描述 
<p>
字符串编辑（Editing.pas\c\cpp） <br><br>【题目描述】 <br>　　为了对一些资料进行保密，奶牛们要对某些文章进行编辑。编辑的方法很奇特：要把原有文章的某些词句按照某些规则用另一些词句代替。<br>　　规则的形式如下：原串&#61672;新串，表示把原串替换成新串。假设有n条规则,第i规则的原串和新串分别为Mi和Ni,则编辑按如下过程进行：开始编辑时，先使用第一条规则，把文章中出现的第一个M1替换成N1，如果替换后的新文章还存在M1，则如上处理，直到文章不存在M1为止；然后用同样的方法使用第2，第3，……，第n条规则进行替换，直到所有的规则都用完为止。注意：<br>　　每次都要从文章开头开始找要替换的词句<br>　　一条规则一旦使用完后，将不能再使用<br>　　每一篇文章都是可编辑的<br>　　如有四条规则：1. ban&#61672;bab  2. baba&#61672;be  3. ana&#61672;any  4. ba b &#61672;hind the g     要编辑的文章为“banana boat”，则编辑的过程如下：<br><br><center><img src="/source/joyoi/tyvj-3364/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM2NC9wcm9ibGVtc19pbWFnZXMvMjE1MC8xLmpwZw==.jpg"></img></center><br>　　编辑后的文章为“behind the goat”。请编写一程序，帮助组委会对给定的文章进行编辑。</p> 

 
 # 输入格式 
<p>
　　输入文件editing.in：<br>　　文件共有2n+2行。文件的第一行是一个整数n（1<=n<=10），表示规则的数目；接下来第2i行及第2i+1行分别表示Mi和N(1<=i<=n)，其长度均不超过80个字符，且Mi不为空串；最后一行是要编辑的文章，长度不超过80个字符。行末没有空格。<br></p> 

 
 # 输出格式 
<p>
　　输出文件editing.out：<br>　　文件只有一行，表示编辑后的文章（长度不超过80个字符）。行末也应该没有空格。<br></p> 
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
<tr><td>【输入样例1】
4
ban
bab
baba
be
ana
any
ba b
hind the g
banana boat

【输入样例2】
1
t
sh
toe or top

</td><td>【输出样例1】
behind the goat

【输出样例2】
shoe or shop</td></tr></table>
