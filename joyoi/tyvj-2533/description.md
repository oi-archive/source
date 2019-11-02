# 

 
 # 题目描述 
<p>
As a reward for record milk production, Farmer John has decided to<br>start paying Bessie the cow a small weekly allowance. FJ has a set<br>of coins in N (1 <= N <= 20) different denominations, where each<br>denomination of coin evenly divides the next-larger denomination<br>(e.g., 1 cent coins, 5 cent coins, 10 cent coins, and 50 cent coins).<br>Using the given set of coins, he would like to pay Bessie at least<br>some given amount of money C (1 <= C <= 100,000,000) every week.<br>Please help him compute the maximum number of weeks he can pay<br>Bessie.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and C<br><br>* Lines 2..N+1: Each line corresponds to a denomination of coin and<br>        contains two integers: the value V (1 <= V <= 100,000,000) of<br>        the denomination, and the number of coins B (1 <= B <=<br>        1,000,000) of this denomation in Farmer John's possession.<br><br>有N种Coin,每周至少要给牛C元钱.<br>下面再给出每种Coin的面值及个数<br>问最多可以支付多少星期.</p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the number of weeks Farmer John can<br>        pay Bessie at least C allowance<br><br></p> 
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
<tr><td>3 6
10 1
1 100
5 120

INPUT DETAILS:

FJ would like to pay Bessie 6 cents per week.  He has 100 1-cent coins,
120 5-cent coins, and 1 10-cent coin.
</td><td>111

OUTPUT DETAILS:

FJ can overpay Bessie with the one 10-cent coin for 1 week, then pay Bessie
two 5-cent coins for 10 weeks and then pay Bessie one 1-cent coin and one
5-cent coin for 100 weeks.</td></tr></table>
