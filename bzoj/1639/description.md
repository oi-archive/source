
# Description

<div class="content"><p><span style="font-size: medium">Farmer John是一个令人惊讶的会计学天才，他已经明白了他可能会花光他的钱，这些钱本来是要维持农场每个月的正常运转的。他已经计算了他以后N(1&lt;=N&lt;=100,000)个工作日中每一天的花费moneyi(1&lt;=moneyi&lt;=10,000)，他想要为他连续的M(1&lt;=M&lt;=N)个被叫做“清算月”的结帐时期做一个预算，每一个“清算月”包含一个工作日或更多连续的工作日，每一个工作日都仅被包含在一个“清算月”当中。 FJ的目标是安排这些“清算月”，使得每个清算月的花费中最大的那个花费达到最小，从而来决定他的月度支出限制。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行：两个用空格隔开的整数：N和M </span></p>
<p><span style="font-size: medium">第2..N+1行：第i+1行包含FJ在他的第i个工作日的花费</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第一行：能够维持每个月农场正常运转的钱数 </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 5<br/>
100<br/>
400<br/>
300<br/>
100<br/>
500<br/>
101<br/>
400<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">500<br/>
输入细节 <br/>
<br/>
这里有7个工作日来被5个“清算月”划分。他花费100，400，100，500，101，和400元在他的每个工作日。 <br/>
<br/>
输出细节 <br/>
<br/>
如果FJ安排他的月度预算，他将把前两天划分在一个月中，把第三天、第四天划分在一个月当中，最后的三个工作日各自在一个月当中，所以他一个月最多花费500元，其他的方法总是得出一个较大的结果。 <br/>
<br/>
100 400   300 100   500   101   400   每天花费<br/>
---1---   ---2---   -3-   -4-   -5-   月度标号<br/>
  500       400     500   101   400   月度花费<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

