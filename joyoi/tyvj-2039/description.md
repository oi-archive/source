# 

 
 # 题目背景 
“扫地”杯III&nbsp;NOIP2012模拟赛&nbsp;day1&nbsp;第二题<br><br><br><br> 

 
 # 题目描述 
liouzhou_101最悲痛的回忆就是NOI2011的道路修建，当时开了系统堆栈，结果无限RE…<br>出于某种报复心理，就把那题神奇了一下：<br>在Z星球上有N个国家，这N个国家之间只能建造N-1条道路且全部建完这N-1条道路后这N个国家相互连通，修建每条道路都有相应的花费。但是他们都很吝啬，于是决定只随机选出两个不同的国家(为了国家的平等，当然这两个国家是无顺序可言的)，建造该建造的道路，使得这两个国家相互连通，自然费用越少越好。然后问你，在所有情况中，修建道路花费的平均值。<br>假若您认为本题题目叙述太渣，那就形象地描述一遍：给出一棵边上带权的树，求任意两个不同的点的距离的期望值。<br><br><br><br> 

 
 # 输入格式 
第一行包括一个正整数N，N表示国家的数量。<br>接下来N-1行每行包括三个正整数x、y和w，表示国家x和国家y之间有一条花费为w的道路。<br><br><br><br> 

 
 # 输出格式 
仅一行，包含一个最简分数，格式为A/B，详见样例。<br><br><br> 

 
 # 提示 
对于这组测资，共存在6种情况：<br>①(1,2)&nbsp;距离&nbsp;1；&nbsp;②(1,3)&nbsp;距离&nbsp;1；<br>③(1,4)&nbsp;距离&nbsp;1；&nbsp;④(2,3)&nbsp;距离&nbsp;2；<br>⑤(2,4)&nbsp;距离&nbsp;2；&nbsp;⑥(3,4)&nbsp;距离&nbsp;2；<br>所以平均值为(1+1+1+2+2+2)/6=3/2。<br><br>30%的数据，满足n&lt;=1,000；<br>50%的数据，满足n&lt;=10,000；<br>100%的数据，满足1&lt;=n&lt;=100,000，1&lt;=w&lt;=1,000。<br><br><br><br>liouzhou_101<br><br><br><br> 
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
1 2 1
1 3 1
1 4 1



</td><td>3/2


</td></tr></table>
