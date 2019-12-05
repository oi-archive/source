# 

 
 # 题目背景 
农民John的牛喜欢玩硬币，所以John就为它们发明了一个新的两人硬币游戏，叫做Xoinc。<BR> 

 
 # 题目描述 
最初地面上有一堆n个硬币(5&lt;=n&lt;=2000)，从上面数第i个硬币的价值为C_i(1&lt;=C_i&lt;=100000);<BR><BR>游戏开始后，A先取一枚或两枚硬币。如果A取了一枚，那么B可以继续取一枚或两枚；如果A取了两枚，那么B可以取一到四枚硬币。每次都只能从最上面取。每一次，当前取硬币的人都至少取一枚硬币，最多可以取他的对手上一次取硬币数目的两倍。当没有硬币可取的时候，游戏就结束了。<BR><BR>然后，他们就可以用得到的硬币向John买东西，当然，他们游戏的目的就是要尽可能使自己得到的硬币价值更大。现在你的任务是，求出在两个人都想得到更大价值的情况下，游戏结束后，第一个人最多能得到的硬币价值。<BR> 

 
 # 输入格式 
第1行：&nbsp;一个整数，N（5&lt;=N&lt;=2000）。&nbsp;<BR><BR>第2到n+1行：&nbsp;第&nbsp;i+1&nbsp;行代表从上数第i枚硬币的价值。 

 
 # 输出格式 
一行：一个数字，第一个人能得到的最大价值 

 
 # 提示 
usaco&nbsp;nov09&nbsp;Ag&nbsp;<BR>translated&nbsp;by&nbsp;pricez 
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
1
3
1
7
2</td><td>9
</td></tr></table>
