# 

 
 # 题目背景 
<p>蛟川书院模拟试题</p> 

 
 # 题目描述 
<p>对于集合N={1,2,&hellip;,n}的子集，定义一个称之为&ldquo;小于&rdquo;的关系：<br />
设S1={X1,X2,&hellip;,Xi}，（X1&lt;X2&lt;&hellip;&lt;Xi），S2={Y1,&nbsp;Y2,&nbsp;&hellip;,Yj}，（Y1&lt;Y2&lt;&hellip;&lt;Yj），如果存在一个k，（0&le;k&le;min(i,j)），使得X1=Y1，&hellip;，Xk=Yk，且k=i或X(k+1)&lt;Y(k+1)，则称S1&ldquo;小于&rdquo;S2。<br />
你的任务是，对于任意的n(n&le;31)及k(k&lt;2n)，求出第k小的子集。</p> 

 
 # 输入格式 
<p>输入文件仅一行，包含两个用空格隔开的自然数，n和k。</p> 

 
 # 输出格式 
<p>输出文件仅一行，使该子集的元素，由小到大排列。空集输出0。</p> 

 
 # 提示 
<p>Moe-ing</p> 
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
<tr><td>3 4</td><td>1 2 3</td></tr></table>
