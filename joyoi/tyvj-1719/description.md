# 

 
 # 题目描述 
今天晚上是大毛的生日宴会，大毛妈妈买了一个大蛋糕，分给他和他的朋友们一起吃。这块蛋糕由n*(n+1)/2个格子组成，构成等腰直角三角形的形状，直角边的长度为n，蛋糕上每个格子都有自己的“美味值”。如下（n=4）：<BR>1&nbsp;6&nbsp;–5&nbsp;4<BR>-2&nbsp;9&nbsp;3<BR>0&nbsp;1<BR>3<BR>大毛想将蛋糕沿着格子的边线恰好切成n块矩形，且使得其中最难吃的一块蛋糕的“美味值”最大。（一块蛋糕的“美味值”定义为其中每格的“美味值”之和，美味值越大越好吃）<BR> 

 
 # 输入格式 
输入第一行是一个正整数n。<BR>接下来是第2~n+1行，其中第i行有(n+2-i)个整数。表示每格的“美味值”。<BR> 

 
 # 输出格式 
输出包括一行，为这n块蛋糕中最难吃的一块的最大“美味值”（可能是正的、负的或零）。 

 
 # 提示 
样例解释：<BR>如下（同一块蛋糕用同种符号标识）：<BR>####<BR>OOX<BR>OO<BR>@<BR><BR>对于50%的数据，1≤n≤100；<BR>对于100%的数据，1≤n≤300。<BR>所有“美味值”的绝对值≤1,000,000,000。<BR><BR><BR><BR>寒假模拟赛&nbsp;提高组&nbsp;day1-2 
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
<tr><td>4
1 6 -5 4
-2 9 3
0 1
3
</td><td>3
</td></tr></table>
