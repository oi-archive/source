# 

 
 # 题目描述 
<p>题目很简单，给出N个数字，不改变它们的相对位置，在中间加入K个乘号和N-K-1个加号，（括号随便加）使最终结果尽量大。因为乘号和加号一共就是N-1个了，所以恰好每两个相邻数字之间都有一个符号。例如：<br />
N=5,&nbsp;K=2，5个数字分别为1、2、3、4、5，可以加成：<br />
1*2*(3+4+5)=24<br />
1*(2+3)*(4+5)=45<br />
(1*2+3)*(4+5)=45<br />
&hellip;&hellip;</p> 

 
 # 输入格式 
<p>输入文件共有二行，第一行为两个有空格隔开的整数，表示N和K，其中(2&lt;=N&lt;=15,&nbsp;0&lt;=K&lt;=N-1)。第二行为&nbsp;N个用空格隔开的数字（每个数字在0到9之间）。</p> 

 
 # 输出格式 
<p>输出文件仅一行包含一个整数，表示要求的最大的结果<br />
最后的结果&lt;=maxlongint</p> 

 
 # 提示 
<p>对于30%的数据，N&lt;=&nbsp;10；<br />
对于全部的数据，N&nbsp;&lt;=&nbsp;100。</p> 
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
<tr><td>5 2
1 2 3 4 5</td><td>120</td></tr></table>
