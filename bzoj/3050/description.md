
# Description

<div class="content"><p><span style="font-size: medium">To earn some extra money, the cows have opened a restaurant in their barn specializing in milkshakes. The restaurant has N seats (1 &lt;= N &lt;= 500,000) in a row. Initially, they are all empty. Throughout the day, there are M different events that happen in sequence at the restaurant (1 &lt;= M &lt;= 300,000). The two types of events that can happen are: 1. A party of size p arrives (1 &lt;= p &lt;= N). Bessie wants to seat the party in a contiguous block of p empty seats. If this is possible, she does so in the lowest position possible in the list of seats. If it is impossible, the party is turned away. 2. A range [a,b] is given (1 &lt;= a &lt;= b &lt;= N), and everybody in that range of seats leaves. Please help Bessie count the total number of parties that are turned away over the course of the day. </span></p>
<p></p>
<div><span style="font-size: 12pt">m(m&lt;=300,000)</span><span style="font-size: 12pt">个操作。操作分</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">种：</span></div>
<div style="text-indent: -18pt; margin: 0cm 0cm 0pt 29.25pt"><span style="font-size: 12pt">1.</span><span style="font-size: 12pt">A p</span><span style="font-size: 12pt">，表示把编号最小的空着的长度为</span><span style="font-size: 12pt">p</span><span style="font-size: 12pt">的区间图上颜色。</span></div>
<div style="text-indent: -18pt; margin: 0cm 0cm 0pt 29.25pt"><span style="font-size: 12pt">2.</span><span style="font-size: 12pt">L a b</span><span style="font-size: 12pt">，表示把从</span><span style="font-size: 12pt">a</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">b</span><span style="font-size: 12pt">的区间（包括端点）全部擦干净（没颜色还是没颜色）。</span></div>
<div><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">：有多少个操作</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">不能实现？</span></div>
<div> </div></div>

# Input

<div class="content"><p> </p>
<p><span style="font-size: medium">* Line 1: Two space-separated integers, N and M. <br/>
* Lines 2..M+1: Each line describes a single event. It is either a line of the form &#34;A p&#34; (meaning a party of size p arrives) or &#34;L a b&#34; (meaning that all cows in the range [a, b] leave).<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"> * Line 1: The number of parties that are turned away. </span></p>
<p> </p></div>

# Sample Input

<div class="content"><span class="sampledata">10 4 <br/>
A 6 <br/>
L 2 4 <br/>
A 5 <br/>
A 2<br/>
 INPUT DETAILS: There are 10 seats, and 4 events. First, a party of 6 cows arrives. Then all cows in seats 2..4 depart. Next, a party of 5 arrives, followed by a party of 2. <br/>
<br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
<br/>
OUTPUT DETAILS: Party #3 is turned away. All other parties are seated. <br/>
<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: 12pt">样例解释：</span></div><br/>
<div><span style="font-size: 12pt">  </span><span style="font-size: 12pt">首先将</span><span style="font-size: 12pt">1~6</span><span style="font-size: 12pt">图上颜色，再把</span><span style="font-size: 12pt">2~4</span><span style="font-size: 12pt">擦掉，这时不存在长度为</span><span style="font-size: 12pt">5</span><span style="font-size: 12pt">的空着的区间，该操作不能实现，跳过。最后把</span><span style="font-size: 12pt">2~3</span><span style="font-size: 12pt">图上颜色。所以不能实现的操作</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">有一个，即第三个操作。</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

