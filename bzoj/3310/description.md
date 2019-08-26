
# Description

<div class="content"><p><span style="font-size: medium">Farmer John&#39;s new barn consists of a huge circle of N stalls (2 &lt;= N &lt;= 3,000,000), numbered 0..N-1, with stall N-1 being adjacent to stall 0. At the end of each day, FJ&#39;s cows arrive back at the barn one by one, each with a preferred stall they would like to occupy. However, if a cow&#39;s preferred stall is already occupied by another cow, she scans forward sequentially from this stall until she finds the first unoccupied stall, which she then claims. If she scans past stall N-1, she continues scanning from stall 0. Given the preferred stall of each cow, please determine the smallest index of a stall that remains unoccupied after all the cows have returned to the barn. Notice that the answer to this question does not depend on the order in which the cows return to the barn. In order to avoid issues with reading huge amounts of input, the input to this problem is specified in a concise format using K lines (1 &lt;= K &lt;= 10,000) each of the form: X Y A B One of these lines specifies the preferred stall for XY total cows: X cows prefer each of the stalls f(1) .. f(Y), where f(i) = (Ai + B) mod N. The values of A and B lie in the range 0...1,000,000,000. Do not forget the standard memory limit of 64MB for all problems. </span></p>
<p><b><span style="font-size: 12pt; font-family: 宋体; background-position: initial initial; background-repeat: initial initial;">有<span lang="EN-US">n</span>个位置绕成一个环，编号为（<span lang="EN-US">0...n-1)</span>，有很多头牛，每头牛喜欢一个位置并且会占领它，如果这个 位置已经有了牛便会向后找到第一个没有牛的位置占领；由于数据过大，采用更高端的方法读入，读入<span lang="EN-US">x </span>，<span lang="EN-US">y</span>，<span lang="EN-US">a</span>，<span lang="EN-US">b</span>表示有<span lang="EN-US">x</span>个牛喜欢<span lang="EN-US">f(1)..f(y),f(i) = (a*i+b)%n;</span></span></b></p>
<p class="MsoNormal"><span lang="EN-US" style="font-size:12.0pt;font-family:宋体"><o:p></o:p></span></p>
<p></p>
<p></p></div>

# Input

<div class="content"><p><font size="4"> * Line 1: Two space-separated integers: N and K. </font></p>
<p><font size="4"> * Lines 2..1+K: Each line contains integers X Y A B, interpreted as above. The total number of cows specified by all these lines will be at most N-1. Cows can be added to the same stall by several of these lines. </font></p></div>

# Output

<div class="content"><p><font size="4"> * Line 1: The minimum index of an unoccupied stall. <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 3<br/>
3 2 2 4<br/>
2 1 0 1<br/>
1 1 1 7 <br/>
<br/>
INPUT DETAILS: There are 10 stalls in the barn, numbered 0..9. The second line of input states that 3 cows prefer stall (2*1+4) mod 10 = 6, and 3 cows prefer stall (2*2+4) mod 10 = 8. The third line states that 2 cows prefer stall (0*1+1) mod 10 = 1. Line four specifies that 1 cow prefers stall (1*1+7) mod 10 = 8 (so a total of 4 cows prefer this stall). </span></div>

# Sample Output

<div class="content"><span class="sampledata">5 <br/>
OUTPUT DETAILS: All stalls will end up occupied except stall 5. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

