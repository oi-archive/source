
# Description

<div class="content"><p><span style="font-size: medium">Farmer John&#39;s arch-nemesis, Farmer Paul, has decided to sabotage Farmer John&#39;s milking equipment! The milking equipment consists of a row of N (3 &lt;= N &lt;= 100,000) milking machines, where the ith machine produces M_i units of milk (1 &lt;= M_i &lt;= 10,000). Farmer Paul plans to disconnect a contiguous block of these machines -- from the ith machine up to the jth machine (2 &lt;= i &lt;= j &lt;= N-1); note that Farmer Paul does not want to disconnect either the first or the last machine, since this will make his plot too easy to discover. Farmer Paul&#39;s goal is to minimize the average milk production of the remaining machines. Farmer Paul plans to remove at least 1 cow, even if it would be better for him to avoid sabotage entirely. Fortunately, Farmer John has learned of Farmer Paul&#39;s evil plot, and he is wondering how bad his milk production will suffer if the plot succeeds. Please help Farmer John figure out the minimum average milk production of the remaining machines if Farmer Paul does succeed. </span></p>
<p>约翰的牧场里有 N 台机器，第 i 台机器的工作能力为 Ai。保罗阴谋破坏一些机器，使得约翰的<br/>
工作效率变低。保罗可以任意选取一段编号连续的机器，使它们停止工作。但这样的破坏只能搞一次，<br/>
而且保罗无法破坏第一台或最后一台机器。请问他该破坏哪些机器才能让剩下机器的工作效率的平均<br/>
数最小？为了显示存在感，保罗至少必须破坏一台机器。</p></div>

# Input

<div class="content"><p><font size="4">* Line 1: The integer N. </font></p>
<p><font size="4">* Lines 2..1+N: Line i+1 contains M_i.</font></p>
<p><font size="4"> </font></p></div>

# Output

<div class="content"><p><font size="4">* Line 1: The lowest possible average Farmer Paul can achieve, rounded to 3 digits after the decimal point, and printed with 3 digits after the decimal point. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
5 <br/>
1 <br/>
7 <br/>
8 <br/>
2<br/>
<br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2.667 <br/>
OUTPUT DETAILS: The optimal solution is to remove the 7 and 8, leaving 5, 1, and 2, whose average is 8/3. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

