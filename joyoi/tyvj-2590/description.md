# 

 
 # 题目描述 
<p>
Farmer John made a profit last year! He would like to invest it<br>well but wonders how much money he will make. He knows the interest<br>rate R (an integer between 0 and 20) that is compounded annually<br>at his bank.  He has an integer amount of money M in the range<br>100..1,000,000.  He knows how many years Y (range: 0..400) he intends<br>to invest the money in the bank. Help him learn how much money he<br>will have in the future by compounding the interest for each year<br>he saves.  Print an integer answer without rounding. Answers for the test<br>data are guaranteed to fit into a signed 32 bit integer.<br><br>一个人要走遍一个农场，每条路都要走两次，但每次的方向都不同。其实就是给定n个点，m条边，双向欧拉回路</p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: R, M, and Y<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the number of dollars FJ will have<br>        after Y years.<br><br></p> 
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
<tr><td>5 5000 4

INPUT DETAILS:

5% annual interest, 5000 money, 4 years

</td><td>6077

OUTPUT DETAILS:

Year 1: 1.05 * 5000 = 5250
Year 2: 1.05 * 5250 = 5512.5
Year 3: 1.05 * 5512.50 = 5788.125
Year 4: 1.05 * 5788.125 = 6077.53125
The integer part of 6077.53125 is 6077.</td></tr></table>
