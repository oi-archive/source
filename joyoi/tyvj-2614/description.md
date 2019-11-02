# 

 
 # 题目描述 
<p>
每天Farmer John的N头奶牛(1 <= N <= 100000，编号1…N)从粮仓走向他的自己的牧场。牧场构成了一棵树，粮仓在1号牧场。恰好有N-1条道路直接连接着牧场，使得牧场之间都恰好有一条路径相连。第i条路连接着A_i，B_i，(1 <= A_i <= N; 1 <= B_i <= N)。奶牛们每人有一个私人牧场P_i (1 <= P_i <= N)。粮仓的门每次只能让一只奶牛离开。耐心的奶牛们会等到他们的前面的朋友们到达了自己的私人牧场后才离开。首先奶牛1离开，前往P_1；然后是奶牛2，以此类推。当奶牛i走向牧场P_i时候，他可能会经过正在吃草的同伴旁。当路过已经有奶牛的牧场时，奶牛i会放慢自己的速度，防止打扰他的朋友。<br>考虑如下的牧场结构（括号内的数字代表了牧场的所有者）。<br><br><img border="0" src="/source/joyoi/tyvj-2614/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYxNC9wcm9ibGVtc19pbWFnZXMvMzA1NS8xNzgyLmpwZw==.jpg"> </p> 

 
 # 输入格式 
<p>
* 第1行 :  一个正整数N<br><br>* 第2…N行:  第i+1行包括一对正整数A_i,B_i<br><br>* 第N+1..N+N行: 第 N+i行 包括一个正整数: P_i<br><br></p> 

 
 # 输出格式 
<p>
* 第一行到第N行：第i行表示第i只奶牛需要被放慢的次数<br><br></p> 
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
1 4
5 4
1 3
2 4
4
2
1
5
3
</td><td>0
1
0
2
1
</td></tr></table>
