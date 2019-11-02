# 

 
 # 题目背景 
（Rainbow和Freda正在城堡里玩得开心的时候，外面传来一阵声音：小猫乖乖，把门开开~）<BR>Rainbow：不好！是汪星人入侵！<BR>Freda：肿么办肿么办T_T？<BR>Rainbow：我们先躲起来观察一下汪星人的动态吧&gt;_&lt;！ 

 
 # 题目描述 
Rainbow和Freda躲到了瞭望塔里，发现汪星人这次的目标有些奇怪。<BR>Rainbow的城堡有N扇门，从1到N标号，它们初始时都是关着的。现在来了N只汪星人，第i只汪星人会把所有标号能被i整除的门的状态改变（即把标号能被i整除的关着的门打开，把标号能被i整除的开着的门关上）。<BR>Rainbow为城堡定义了一个不安全指数——即最后打开着的门的数目。Rainbow想请你帮忙计算，城堡的不安全指数是多少？ 

 
 # 输入格式 
每个测试点包括多组测试数据。<BR>第一行一个整数T，表示一共有T组测试数据。<BR>接下来T行每行一个整数N，表示Rainbow城堡的门的数量。 

 
 # 输出格式 
输出T行，第i行的数字表示，对于第i个N，城堡的不安全指数。 

 
 # 提示 
样例解释:　　　<BR>当N=4的时候，4扇门情况如下（1表示开，0表示关）：<BR>没有汪星人来的时候：0000<BR>第一只汪星人来后：1111<BR>第二只汪星人来后：1010<BR>第三只汪星人来后：1000<BR>第四只汪星人来后：1001<BR>所以答案为2<BR>对于20%的数据，T&lt;=100.<BR>对于100%的数据，T&lt;=20000，N&lt;=50000. 
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
4
10
16
27</td><td>2
3
4
5</td></tr></table>
