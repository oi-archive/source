
# Description

<div class="content"><p><span style="font-size: medium">正如你所知，奶牛们没有手指以至于不能玩“石头剪刀布”来任意地决定例如谁先挤奶的顺序。她们甚至也不能通过仍硬币的方式。 所以她们通过&#34;round number&#34;竞赛的方式。第一头牛选取一个整数，小于20亿。第二头牛也这样选取一个整数。如果这两个数都是 &#34;round numbers&#34;，那么第一头牛获胜，否则第二头牛获胜。 如果一个正整数N的二进制表示中，0的个数大于或等于1的个数，那么N就被称为 &#34;round number&#34; 。例如，整数9，二进制表示是1001，1001 有两个&#39;0&#39;和两个&#39;1&#39;; 因此，9是一个round number。26 的二进制表示是 11010 ; 由于它有2个&#39;0&#39;和 3个&#39;1&#39;，所以它不是round number。 很明显，奶牛们会花费很大精力去转换进制，从而确定谁是胜者。 Bessie 想要作弊，而且认为只要她能够知道在一个指定区间范围内的&#34;round numbers&#34;个数。 帮助她写一个程序，能够告诉她在一个闭区间中有多少Hround numbers。区间是 [start, finish]，包含这两个数。 (1 &lt;= Start &lt; Finish &lt;= 2,000,000,000) </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: 两个用空格分开的整数，分别表示Start 和 Finish。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: Start..Finish范围内round numbers的个数 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
输出解释:<br/>
<br/>
 2    10  1x0 + 1x1  ROUND<br/>
 3    11  0x0 + 2x1  NOT round<br/>
 4   100  2x0 + 1x1  ROUND<br/>
 5   101  1x0 + 2x1  NOT round<br/>
 6   110  1x0 + 2x1  NOT round<br/>
 7   111  0x0 + 3x1  NOT round<br/>
 8  1000  3x0 + 1x1  ROUND<br/>
 9  1001  2x0 + 2x1  ROUND<br/>
10  1010  2x0 + 2x1  ROUND<br/>
11  1011  1x0 + 3x1  NOT round<br/>
12  1100  2x0 + 2x1  ROUND<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

