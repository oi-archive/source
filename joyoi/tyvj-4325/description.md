# 

 
 # 题目背景 
<p>现有一个网络服务器，每秒能处理一个请求。</p> 

 
 # 题目描述 
<p>客户端向服务器发送了N个请求。每个请求有一个收益值X和失效时间Y。服务器必须在时间Y之前处理这个请求，才能得到X的收益值。</p>

<p>请问服务器处理这些请求所能得到的最大收益值是多少。</p> 

 
 # 输入格式 
<p>第一行，一个整数N</p>

<p>之后N行，每行两个整数X,Y，代表一个请求的收益值和失效时间。</p> 

 
 # 输出格式 
<p>一个整数，表示最大收益值。</p> 

 
 # 提示 
<p>1&lt;=N&lt;=200000</p>

<p>1&lt;=X&lt;=1000</p>

<p>1&lt;=Y&lt;=200000</p> 
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
<tr><td>5
556 16999
251 22996
810 19556
41 12170
324 6920
</td><td>1982</td></tr></table>
