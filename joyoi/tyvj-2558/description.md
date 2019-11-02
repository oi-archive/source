# 

 
 # 题目描述 
<p>
The 2*N (3 <= N <= 1,000) cows have assembled the Bovine Accordion<br>and Banjo Orchestra!  They possess various levels of skill on their<br>respective instruments: accordionist i has an associated talent<br>level A_i (0 <= A_i <= 1,000); banjoist j has an associated talent<br>level B_j (0 <= B_j <= 1,000).<br><br>The combined `awesomeness' of a pairing between cows with talents<br>A_i and B_j is directly proportional to the talents of each cow in<br>the pair so a concert with those two cows will earn FJ precisely<br>A_i * B_j dollars in "charitable donations".  FJ wishes to maximize<br>the sum of all revenue obtained by his cows by pairing them up in<br>the most profitable way.<br><br>有二个数列，每行N个。你可以将第一行的某个数A与第二行的某个B连接起来，得到的收益为这两个数的乘积 <br>而A之前的那些没有连线的数，将其值累加起来再平方，这个数为你的损失，B之前的那些没有连线的数将其值 <br>累加起来再平方，这个数也为你的损失,现在希望你的收益值越大越好，请问其值可以为多少？ <br>注意你所连出来的线不能交叉 <br><br><br>Input <br><br>第一行给出数字N, (3 <= N <= 1,000) <br>下面N行给出第一个数列的N个数,其值在[0,1000] <br>再下面N行给出第二个数列的N个数其值在[0,1000] <br><br><br>Output <br><br>你的最大收益值. <br><br>Unfortunately, FJ's accordionists are a bit stuck up and stubborn.<br>If accordionist i is paired with banjoist j, then accordionists<br>i+1..N refuse to be paired with banjoists 1..j-1. This creates<br>restrictions on which pairs FJ can form. FJ thus realizes that in<br>order to maximize his profits, he may have to leave some cows<br>unpaired.<br><br>To make matters worse, when one or more of the musicians is skipped,<br>they will be greatly upset at their wasted talent and will engage<br>in massive binge drinking to wash away their sorrows.<br><br>After all pairings are made, a list is constructed of the groups<br>of each of the consecutive skipped musicians (of either instrument).<br>Every group of one or more consecutive skipped cows will gather<br>together to consume kegs of ice cold orange soda in an amount<br>proportional to the square of the sum of their wasted talent.<br><br>Specifically, FJ has calculated that if the x-th to y-th accordionists<br>are skipped, they will consume precisely (A_x + A_x+1 + A_x+2 + ...<br>+ A_y)^2 dollars worth of orange soda in the process of drinking<br>themselves into oblivion. An identical relationship holds for the<br>banjoists. FJ realizes that he'll end up getting stuck with the<br>bill for his cows' drinking, and thus takes this into account when<br>choosing which pairings to make.<br><br>Find the maximum amount of total profit that FJ can earn after the<br>contributions are collected and the orange soda is paid for.<br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer: N<br><br>* Lines 2..N+1: Line i+1 contains the single integer: A_i<br><br>* Lines N+2..2*N+1: Line i+N+1 contains the single integer: B_i<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that represents the maximum amount of cash<br>        that FJ can earn.<br><br></p> 
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
<tr><td>3
1
1
5
5
1
1

INPUT DETAILS:

There are 6 cows: 3 accordionists and 3 banjoists. The accordionists have
talent levels (1, 1, 5), and the banjoists have talent levels (5, 1, 1).

</td><td>17

OUTPUT DETAILS:

FJ pairs accordionist 3 with banjoist 1 to get earn A_3 * B_1 = 5 * 5 = 25
in profit.  He loses a total of (1 + 1)^2 + (1 + 1)^2 = 8 dollars due to
the cost of soda for his remaining cows. Thus his final (net) profit is 25
- 8 = 17.</td></tr></table>
