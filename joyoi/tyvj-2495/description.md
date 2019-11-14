# 

 
 # 题目描述 
<p>
Farmer John went to cut some wood and left N (2 <= N <= 100,000)<br>cows eating the grass, as usual. When he returned, he found to his<br>horror that the cows were in his garden eating his beautiful flowers.<br>Wanting to minimize the subsequent damage, FJ decided to take<br>immediate action and transport the cows back to their barn.<br><br>Each cow i is at a location that is Ti minutes (1 <= Ti <= 2,000,000)<br>away from the barn. Furthermore, while waiting for transport, she<br>destroys Di (1 <= Di <= 100) flowers per minute. No matter how hard<br>he tries,FJ can only transport one cow at a time back to the barn.<br>Moving cow i to the barn requires 2*Ti minutes (Ti to get there and<br>Ti to return).<br><br>Write a program to determine the order in which FJ should pick up<br>the cows so that the total number of flowers destroyed is minimized.<br><br>//有六头牛，下面六行给出每头牛回家的路所要花的时间，以及它在每个时间摧毁花的数目<br>//John每次送一头牛回家，再返回来.希望将所有牛都送回家，然后被摧的花的总数最少.<br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer N<br><br>* Lines 2..N+1: Each line contains two space-separated integers, Ti<br>        and Di, that describe a single cow's characteristics<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the minimum number of destroyed<br>        flowers<br></p> 
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
3 1
2 5
2 3
3 2
4 1
1 6
</td><td>86

OUTPUT DETAILS:

FJ returns the cows in the following order: 6, 2, 3, 4, 1, 5. While
he is transporting cow 6 to the barn, the others destroy 24 flowers;
next he will take cow 2, losing 28 more of his beautiful flora. For
the cows 3, 4, 1 he loses 16, 12, and 6 flowers respectively. When
he picks cow 5 there are no more cows damaging the flowers, so the
loss for that cow is zero. The total flowers lost this way is 24 +
28 + 16 + 12 + 6 = 86.</td></tr></table>
