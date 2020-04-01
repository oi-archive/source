# 

 
 # 题目描述 
<p>
你的任务是计算一个函数F(x, y)，其中x和y是两个正整数序列。F的定义如下：<br><br>boolean F(x, y)<br><br>   if W(x) ≠ W(y) then return 0<br><br>   else if |W(x)| = |W(y)| = 1 then return 1<br><br>   else return F(p(x), p(y)) AND F(s(x), s(y)).<br><br> <br><br>W(x)表示序列x中元素的集合。（元素的顺序和出现次数将被无视）<br><br>p(x)表示序列x的最长前缀，满足：W(x) ≠ W(p(x))<br><br>s(x)表示序列x的最长后缀。满足：W(x) ≠ W(s(x))<br><br>|Z|表示集合Z中元素个数<br><br> <br><br></p> 

 
 # 输入格式 
<p>
第一行k表示数据组数。<br>对于每组数据，第一行n,m分别表示x序列的长度与y序列的长度，第二行n个数表示xi，第三行m个数表示yi<br>1<=k<=13<br>1<=n,m<=100000<br>1<=xi,yi<=100<br><br><br></p> 

 
 # 输出格式 
<p>
k行，对于每组数据，若F(x,y)为真输出1，否则输出0。<br></p> 

 
 # 提示 
<p>
感谢MT大牛贡献译文.</p> 
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
<tr><td>2
4 5
3 1 2 1
1 3 1 2 1
7 7
1 1 2 1 2 1 3
1 1 2 1 3 1 3
</td><td>0
1</td></tr></table>
