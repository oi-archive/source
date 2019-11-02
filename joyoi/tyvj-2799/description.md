# 

 
 # 题目描述 
<p>
蜗牛们居住在一棵有N(N<=100000)个结点的树上，蜗牛们都居住在结点上。假设每只蜗牛的爬行速度都是一样的，树的每条边的长度代表着蜗牛通过需要的时间。<br>如果在结点X上的蜗牛到达结点Y的时间不超过K，(X<>Y),则我们认为这两个结点X,Y是邻近的。给定蜗牛们居住的树，求有多少对结点是邻近的？<br></p> 

 
 # 输入格式 
<p>
第一行两个整数N, K。<br>以后N-1行每行3个整数A,B,L，表示A,B间有一条边,爬行时间为L.<br>输入保证所有边的长度和<=maxlongint.且树为连通。<br></p> 

 
 # 输出格式 
<p>
输出一行，为邻近结点的对数。(X,Y)和(Y,X)只算一对。</p> 

 
 # 提示 
<p>
数据规模：<br>30%的数据N<=5000。<br>100%的数据N<=100000,K<=maxlongint。<br>前5个点时限1s,后5个点2s。</p> 
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
<tr><td>5 4
1 2 3
1 3 1	
1 4 2
3 5 1
</td><td>8</td></tr></table>
