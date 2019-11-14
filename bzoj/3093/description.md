
# Description

<div class="content"><div style="margin: 10.5pt 19.8pt 0pt 0cm; line-height: 12.8pt"><span style="font-size: medium"><span style="color: black">Mr. B and Mr. M like to play with balls. They have many balls colored in blue and red. Firstly, Mr. B randomly picks up N balls out of them and put them into a bag. Mr. M knows that there are N+1 possible situations in which the number of red balls is ranged from 0 to N, and we assume the possibilities of the N+1 situations are the same. But Mr. M does not know which situation occurs. Secondly, Mr. M picks up P balls out of the bag and examines them. There are Q red balls and P-Q blue balls. The question is: if he picks up one more ball out of the bag, what is the possibility that this ball is red? </span></span></div></div>

# Input

<div class="content"><div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">Each test case contains only one line with three integers N, P and Q (2 &lt;= N &lt;= 100,000, 0 &lt;= P &lt;= N-1, 0 &lt;= Q &lt;= P). </span></span></div></div>

# Output

<div class="content"><div style="margin: 9.5pt -1.1pt 0pt 0cm; line-height: 13.5pt" align="left"> </div>
<div style="margin: 0cm 20.35pt 0pt 0cm; line-height: 13pt"><span style="font-size: medium"><span style="color: black">For each test case, display a single line containing the case number and the possibility of the next ball Mr. M picks out is red. The number should be rounded to four decimal places. </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
 <br/>
3  0 0<br/>
4  2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
Case 1: 0.5000 <br/>
Case 2: 0.5000 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
[Explanation] <br/><br/>
For example as the sample test one, there are three balls in the bag. The possibilities of the four possible situations are all 0.25. If there are no red balls in the bag, the possibility of the next ball are red is 0. If there is one red ball in the bag, the possibility is 1/3. If there are two red balls, the possibility is 2/3. Finally if all balls are red, the possibility is 1. So the answer is 0*(1/4)+(1/3)*(1/4)+(2/3)*(1/4)+1*(1/4)=0.5. </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

