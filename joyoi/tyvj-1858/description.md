# 

 
 # 题目背景 
你觉着这种题会有背景？ 

 
 # 题目描述 
神犇LYD虐完HEOI之后给傻×XLk出了一题：<BR>SHY是某国的公主，平时的一大爱好是读诗...(中间略)...结果mod&nbsp;p就可以了<BR><BR>简明题意<BR>给定&nbsp;k,a,n,d,p<BR>f(i)=1^k+2^k+3^k+......+i^k<BR>g(x)=f(1)+f(2)+f(3)+....+f(x)<BR>求(g(a)+g(a+d)+g(a+2d)+......+g(a+nd))mod&nbsp;p<BR><BR>对于所有数据<BR>1&lt;=k&lt;=123<BR>0&lt;=a,n,d&lt;=123456789<BR>p==1234567891<BR> 

 
 # 输入格式 
第一行数据组数，(保证小于6)<BR>以下每行四个整数&nbsp;k,a,n,d 

 
 # 输出格式 
每行一个结果。<BR> 

 
 # 提示 
原创 
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
1 1 1 1
1 1 1 1
1 1 1 1
1 1 1 1
1 1 1 1
</td><td>5
5
5
5
5
</td></tr></table>
