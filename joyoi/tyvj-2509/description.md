# 

 
 # 题目描述 
<p>
Every year the cows hold an event featuring a peculiar version of<br>hopscotch that involves carefully jumping from rock to rock in a<br>river. The excitement takes place on a long, straight river with a<br>rock at the start and another rock at the end, L units away from<br>the start (1 <= L <= 1,000,000,000). Along the river between the<br>starting and ending rocks, N (0 <= N <= 50,000) more rocks appear,<br>each at an integral distance Di from the start (0 < Di < L).<br><br>To play the game, each cow in turn starts at the starting rock and<br>tries to reach the finish at the ending rock, jumping only from<br>rock to rock. Of course, less agile cows never make it to the final<br>rock, ending up instead in the river.<br><br>Farmer John is proud of his cows and watches this event each year.<br>But as time goes by, he tires of watching the timid cows of the<br>other farmers limp across the short distances between rocks placed<br>too closely together. He plans to remove several rocks in order to<br>increase the shortest distance a cow will have to jump to reach the<br>end. He knows he cannot remove the starting and ending rocks, but<br>he calculates that he has enough resources to remove up to M rocks<br>(0 <= M <= N).<br><br>FJ wants to know exactly how much he can increase the shortest<br>distance *before* he starts removing the rocks. Help Farmer John<br>determine the greatest possible shortest distance a cow has to jump<br>after removing the optimal set of M rocks.<br><br>数轴上有n个石子，第i个石头的坐标为Di，现在要从0跳到L，每次条都从一个石子跳到相邻的下一个石子。<br>现在FJ允许你移走M个石子，问移走这M个石子后，相邻两个石子距离的最小值的最大值是多少。</p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: L, N, and M<br><br>* Lines 2..N+1: Each line contains a single integer indicating how far<br>        some rock is away from the starting rock. No two rocks share<br>        the same position.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the maximum of the shortest<br>        distance a cow has to jump after removing M rocks<br><br></p> 
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
<tr><td>25 5 2
2
14
11
21
17

5 rocks at distances 2, 11, 14, 17, and 21. Starting rock at position
0, finishing rock at position 25.
</td><td>4

OUTPUT DETAILS:

Before removing any rocks, the shortest jump was a jump of 2 from
0 (the start) to 2. After removing the rocks at 2 and 14, the
shortest required jump is a jump of 4 (from 17 to 21 or from 21 to
25).</td></tr></table>
