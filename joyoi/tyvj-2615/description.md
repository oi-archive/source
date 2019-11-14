# 

 
 # 题目描述 
<p>
Farmer John has invented a new way of feeding his cows. He lays out<br>N (1 <= N <= 700,000) hay bales conveniently numbered 1..N in a<br>long line in the barn. Hay bale i has weight W_i (1 <= W_i <=<br>2,000,000,000). A sequence of six weights might look something like:<br>        17 5 9 10 3 8 <br>A pair of cows named Bessie and Dessie walks down this line after<br>examining all the haybales to learn their weights. Bessie is the<br>first chooser. They take turns picking haybales to eat as they walk<br>(once a haybale is skipped, they cannot return to it). For instance,<br>if cows Bessie and Dessie go down the line, a possible scenario is:<br><br>* Bessie picks the weight 17 haybale<br>* Dessie skips the weight 5 haybale and picks the weight 9 haybale<br>* Bessie picks the weight 10 haybale<br>* Dessie skips the weight 3 haybale and picks the weight 8 haybale<br>Diagrammatically:<br><br>Bessie   |      |<br>        17 5 9 10 3 8 <br>Dessie       |      |<br>This scenario only shows a single skipped bale; either cow can skip<br>as many as she pleases when it's her turn.Each cow wishes to maximize the total weight of <br>hay she herself consumes (and each knows that the other cow has this goal).Furthermore, a cow <br>will choose to eat the first bale of hay thatmaximimizes her total weight consumed.<br>Given a sequence of hay weights, determine the amount of hay that<br>a pair of cows will eat as they go down the line of hay.<br><br><br>一排数，两个人轮流取数，保证取的位置递增，每个人要使自己取的数的和尽量大，求两个人都在最优策略下取的和各是多少。<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer: N<br><br>* Lines 2..N+1: Line i+1 contains a single integer: W_i<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: Two space-separated integers, the total weight of hay<br>        consumed by Bessie and Dessie respectively<br></p> 
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
<tr><td>6
17
5
9
10
3
8

</td><td>27 17</td></tr></table>
