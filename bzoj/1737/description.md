
# Description

<div class="content"><p><span style="font-size: medium">Goneril is a very sleep-deprived cow. Her day is partitioned into N (3 &lt;= N &lt;= 3,830) equal time periods but she can spend only B (2 &lt;= B &lt; N) not necessarily contiguous periods in bed. Due to her bovine hormone levels, each period has its own utility U_i (0 &lt;= U_i &lt;= 200,000), which is the amount of rest derived from sleeping during that period. These utility values are fixed and are independent of what Goneril chooses to do, including when she decides to be in bed. With the help of her alarm clock, she can choose exactly which periods to spend in bed and which periods to spend doing more critical items such as writing papers or watching baseball. However, she can only get in or out of bed on the boundaries of a period. She wants to choose her sleeping periods to maximize the sum of the utilities over the periods during which she is in bed. Unfortunately, every time she climbs in bed, she has to spend the first period falling asleep and gets no sleep utility from that period. The periods wrap around in a circle; if Goneril spends both periods N and 1 in bed, then she does get sleep utility out of period 1. What is the maximum total sleep utility Goneril can achieve? </span></p>
<div><span style="font-size: medium">贝茜是一只非常缺觉的奶牛．她的一天被平均分割成N段(3≤N≤3830)，但是她要用其中的B段时间(2≤B&lt; N)睡觉．每段时间都有一个效用值Ui(0≤Ui≤200000)，只有当她睡觉的时候，才会发挥效用．    有了闹钟的帮助，贝茜可以选择任意的时间入睡，当然，她只能在时间划分的边界处入睡、醒来．    贝茜想使所有睡觉效用的总和最大．不幸的是，每一段睡眠的第一个时间阶段都是“入睡”阶段，而旦不记入效用值．    时间阶段是不断循环的圆（一天一天是循环的嘛），假如贝茜在时间N和时间1睡觉，那么她将得到时间1的效用值．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: N and B</span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Line i+1 contains a single integer, U_i, between 0 and 200,000 inclusive </span></p>
<div><span style="font-size: medium">    第1行：两个整数，N和B.</span></div>
<div><span style="font-size: medium">    第2到N+1行：每行1个数字，代表了时间i的效用值．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, the maximum total sleep utility Goneril can achieve. </span></p>
<div><span style="font-size: medium">    最大的效用值．</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
2<br/>
0<br/>
3<br/>
1<br/>
4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
选择时间段1（入睡），4，2</span></div>

# Hint

<div class="content"><p></p><p>见国家队2005 Twb,ZgL作业</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

