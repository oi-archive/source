
# Description

<div class="content"><p><span style="font-size: medium">Farmer John is at the market to purchase supplies for his farm. He has in his pocket K coins (1 &lt;= K &lt;= 16), each with value in the range 1..100,000,000. FJ would like to make a sequence of N purchases (1 &lt;= N &lt;= 100,000), where the ith purchase costs c(i) units of money (1 &lt;= c(i) &lt;= 10,000). As he makes this sequence of purchases, he can periodically stop and pay, with a single coin, for all the purchases made since his last payment (of course, the single coin he uses must be large enough to pay for all of these). Unfortunately, the vendors at the market are completely out of change, so whenever FJ uses a coin that is larger than the amount of money he owes, he sadly receives no changes in return! Please compute the maximum amount of money FJ can end up with after making his N purchases in sequence. Output -1 if it is impossible for FJ to make all of his purchases. </span></p>
<p></p>
<p><span style="font-size: medium">K个硬币，要买N个物品。</span></p>
<p><span style="font-size: medium">给定买的顺序，即按顺序必须是一路买过去，当选定买的东西物品序列后，付出钱后，货主是不会找零钱的。现希望买完所需要的东西后，留下的钱越多越好，如果不能完成购买任务，输出-1</span></p></div>

# Input

<div class="content"><p><font size="4">Line 1: Two integers, K and N. </font></p>
<p><font size="4">* Lines 2..1+K: Each line contains the amount of money of one of FJ&#39;s coins. </font></p>
<p><font size="4">* Lines 2+K..1+N+K: These N lines contain the costs of FJ&#39;s intended purchases. </font></p></div>

# Output

<div class="content"><p><font size="4">* Line 1: The maximum amount of money FJ can end up with, or -1 if FJ cannot complete all of his purchases. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 6<br/>
12<br/>
15<br/>
10<br/>
6<br/>
3<br/>
3<br/>
2<br/>
3<br/>
7<br/>
<br/>
INPUT DETAILS: FJ has 3 coins of values 12, 15, and 10. He must make purchases in sequence of value 6, 3, 3, 2, 3, and 7. <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12 <br/>
OUTPUT DETAILS: FJ spends his 10-unit coin on the first two purchases, then the 15-unit coin on the remaining purchases. This leaves him with the 12-unit coin. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

