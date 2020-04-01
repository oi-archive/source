# 

 
 # 题目描述 
<p>有一个n个点，m个边的无向联通图。<br />
有点权，没有边权。<br />
定义一个路径为一列点&nbsp;a_1,&nbsp;a_2,&nbsp;&hellip;&hellip;,&nbsp;a_n，相邻两个之间有边，可以为空。<br />
定义一个路径的值为路径上所有的点权的异或。<br />
问在所有可能为路径值的数中，第k大为多少。</p>

<p>无解输出&quot;-1&quot;。</p> 

 
 # 输入格式 
<p>第一行n,&nbsp;m,&nbsp;k。<br />
以下m行，每行xy表示一个边。<br />
以下一行n个数，表示每个点的权值。</p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p>一行一个整数表示答案。无解输出&quot;-1&quot;。</p> 

 
 # 提示 
<p>n,&nbsp;m&nbsp;&lt;=&nbsp;100000</p>

<p>0&nbsp;&lt;=&nbsp;权值&nbsp;&lt;&nbsp;2^31</p>

<p>0&nbsp;&lt;&nbsp;k&nbsp;&lt;&nbsp;2^31</p>

<p>对于30%的数据，n&nbsp;\leq&nbsp;20。</p> 
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
<tr><td>3 3 3
1 2
2 3
3 1
1 2 4
</td><td>5</td></tr></table>
