# 

 
 # 题目描述 
<p>
The cows are building a roller coaster! They want your help to<br>design as fun a roller coaster as possible, while keeping to the<br>budget.<br><br>The roller coaster will be built on a long linear stretch of land<br>of length L (1 <= L <= 1,000). The roller coaster comprises a<br>collection of some of the N (1 <= N <= 10,000) different interchangable<br>components. Each component i has a fixed length Wi (1 <= Wi <= L).<br>Due to varying terrain, each component i can be only built starting<br>at location Xi (0 <= Xi <= L-Wi). The cows want to string together<br>various roller coaster components starting at 0 and ending at L so<br>that the end of each component (except the last) is the start of<br>the next component.<br><br>Each component i has a "fun rating" Fi (1 <= Fi <= 1,000,000) and<br>a cost Ci (1 <= Ci <= 1000). The total fun of the roller coster is<br>the sum of the fun from each component used; the total cost is<br>likewise the sum of the costs of each component used. The cows'<br>total budget is B (1 <= B <= 1000). Help the cows determine the<br>most fun roller coaster that they can build with their budget.<br><br>有n个区间，长度为Wi，起点为Xi，终点为Xi + Wi，每个区间有一个权值Fi，和一个费用Ci。现在奶牛们要买一些区间，使他们首尾相连，并且第一个区间的起点为0，最后一个区间终点为L，并且他们权值最大。奶牛只有B元钱。</p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: L, N and B.<br><br>* Lines 2..N+1: Line i+1 contains four space-separated integers,<br>        respectively: Xi, Wi, Fi, and Ci.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the maximum fun value that a<br>        roller-coaster can have while staying within the budget and<br>        meeting all the other constraints. If it is not possible to<br>        build a roller-coaster within budget, output -1.<br><br></p> 
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
<tr><td>5 6 10
0 2 20 6
2 3 5 6
0 1 2 1
1 1 1 3
1 2 5 4
3 2 10 2


</td><td>17

OUTPUT DETAILS:

Taking the 3rd, 5th and 6th components gives a connected roller-coaster
with fun value 17 and cost 7. Taking the first two components would
give a more fun roller-coaster (25) but would be over budget.
</td></tr></table>
