# 

 
 # 题目背景 
CDQZ&nbsp;NOIP模拟赛 

 
 # 题目描述 
小A的工作不仅繁琐，更有苛刻的规定，要求小A每天早上在6：00之前到达公司，否则这个月工资清零。可是小A偏偏又有赖床的坏毛病。于是为了保住自己的工资，小A买了一个十分牛B的空间跑路器，每秒钟可以跑2^k千米（k是任意数）。当然，这个机器是用longint存的，所以总跑路长度不能超过maxlongint千米。小A的家到公司的路可以看做一个有向图，小A家为点1，公司为点n，每条边长度均为一千米。小A想每天能醒地尽量晚，所以让你帮他算算，他最少需要几秒才能到公司。数据保证1到n至少有一条路径。 

 
 # 输入格式 
第一行两个整数n，m，表示点的个数和边的个数。<br>接下来m行每行两个数字u，v，表示一条u到v的边。<br> 

 
 # 输出格式 
一行一个数字，表示到公司的最少秒数。 

 
 # 提示 
【样例解释】:　　　<br>1-&gt;1-&gt;2-&gt;3-&gt;4，总路径长度为4千米，直接使用一次跑路器即可。<br>【数据范围】:<br>50%的数据满足最优解路径长度&lt;=1000；<br>100%的数据满足n&lt;=50，m&lt;=10000，最优解路径长度&lt;=maxlongint。 
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
<tr><td>4 4
1 1
1 2
2 3
3 4</td><td>1</td></tr></table>
