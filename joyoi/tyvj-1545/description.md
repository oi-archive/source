# 

 
 # 题目背景 
某村要建水渠<BR> 

 
 # 题目描述 
某村有n-1个住户，v2....vn,其中可建m条水渠，每条水渠有一个代价c,但这个村只有一个水源v1，现要从v1建水渠覆盖所有的住户，求最小代价<BR> 

 
 # 输入格式 
第一行两个整数n，m，含义如题,(2&lt;=n&lt;=100,1&lt;=m&lt;=10000)<BR>以下m行，每行三个整数&nbsp;i&nbsp;j&nbsp;cij，(i!=j,1&lt;=i,j&lt;=n,1&lt;=cij&lt;=100)&nbsp;<BR>表示可建一条从i到j代价为cij的水渠<BR> 

 
 # 输出格式 
若能覆盖所有住户,则输出最小代价<BR>否则,输出impossible<BR> 

 
 # 提示 
这可是中国人发明的算法<BR>北京四中wangmj17 
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
<tr><td>3 3
1 2 3
1 3 5
3 2 1

</td><td>6

</td></tr></table>
