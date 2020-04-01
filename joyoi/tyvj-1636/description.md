# 

 
 # 题目背景 
此题为taophee专辑中的第五题。 

 
 # 题目描述 
Taophee很快就将YH带回来的果子吃了个精光。Taophee突然发现YH的背包底层装了好多金币！Taophee立刻叫来YH，他想知道这些金币总共值多少钱。可是此时YH因为体力消耗过大睡着了，Taophee不忍心打扰她(这个......)，于是Taophee决定自己数。但是Taophee发现了一个问题，就是为了知道背包里有多少钱，而把所有金币一个一个拿出来，那就太麻烦了，因为金币实在是太多了，都拿出来会浪费很多时间，他还要继续旅行。<BR>&nbsp;&nbsp;&nbsp;&nbsp;但这根本难不住聪明的Taophee。他知道空的背包的重量W和装满金币的背包的重量F。还知道一共有N种金币，其中第i种金币的面值为Pi，重量为Wi。知道了这些数据，Taophee马上就能够计算出背包里的金币至少值多少钱。<BR>可是，还有个问题，那就是Taophee太懒了，所以他想请你帮忙，每数完一个背包就会付给你报酬（1个背包100000000000000000000000000&nbsp;mod&nbsp;10美元）请你来帮帮他把。 

 
 # 输入格式 
输入文件第一行为两个正整数W,F(1&lt;=W&lt;=F&lt;=1000)，W为空的背包的重量，F为装满金币的背包的重量。第二行为一个正整数N(1&lt;=N&lt;=100)，表示金币的种类。接下来的N行，每行包含两个整数，第i+2行的两个数Pi和Wi分别表示第i种金币的面值和重量，1&lt;=Pi&lt;=100，1&lt;=Wi&lt;=200。 

 
 # 输出格式 
仅一行，如果所存在最少钱数，则输出一个整数，为钱数X。否则输出一行'This&nbsp;is&nbsp;impossible.&nbsp;'。 
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
<tr><td>10 110
2
1 1
30 50
</td><td>60
</td></tr></table>
