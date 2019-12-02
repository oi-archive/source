# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Fox住在魔法岛上,他种了一排N棵魔法树(标号0..N-1,高度Ai),接下来的M天,每天Del都会来（Del是Fox的朋友）,或者问Fox一些问题,或者帮助Fox对这些树施魔法.于是有两种形式:<BR>&nbsp;&nbsp;&nbsp;&nbsp;1.询问第a棵树到第b棵树的总高度<BR>&nbsp;&nbsp;&nbsp;&nbsp;2.对第a棵树到第b棵树施魔法,使它们长高c单位 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行,两个整数N,M<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行,N个整数,表示fox种的魔法树的初始高度<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来M行,有两种情况<BR>&nbsp;&nbsp;&nbsp;&nbsp;1.Q&nbsp;a&nbsp;b&nbsp;表示询问a到b的高度和<BR>&nbsp;&nbsp;&nbsp;&nbsp;2.C&nbsp;a&nbsp;b&nbsp;c&nbsp;表示对a到b施魔法c 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;M行,对于每一个询问给出一个答案。 

 
 # 提示 
80%的数据保证	N&lt;=100,M&lt;=100<BR>100%的数据保证&nbsp;	N&lt;=2000000,M&lt;=2000,0&lt;=Ai&lt;=100,0&lt;=c&lt;=2500000000<BR>其中：前8组数据每组5分，后两组数据每组30分。来源：fox_pro	开学欢乐赛 
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
<tr><td>10 5
1 2 3 4 5 6 7 8 9 10
Q 3 3
Q 0 9
Q 1 3
C 2 5 3
Q 1 3</td><td>4
55
9
15</td></tr></table>
