
# Description

<div class="content"><p><br/>
在一年前赢得了小镇的最佳草坪比赛后，FJ变得很懒，再也没有修剪过草坪。现在，<br/>
新一轮的最佳草坪比赛又开始了，FJ希望能够再次夺冠。<br/>
<br/>
然而，FJ的草坪非常脏乱，因此，FJ只能够让他的奶牛来完成这项工作。FJ有N<br/>
(1 &lt;= N &lt;= 100,000)只排成一排的奶牛，编号为1...N。每只奶牛的效率是不同的，<br/>
奶牛i的效率为E_i(0 &lt;= E_i &lt;= 1,000,000,000)。<br/>
<br/>
靠近的奶牛们很熟悉，因此，如果FJ安排超过K只连续的奶牛，那么，这些奶牛就会罢工<br/>
去开派对:)。因此，现在FJ需要你的帮助，计算FJ可以得到的最大效率，并且该方案中<br/>
没有连续的超过K只奶牛。<br/>
<br/>
</p></div>

# Input

<div class="content"><p><br/>
* 第一行：空格隔开的两个整数N和K<br/>
<br/>
* 第二到N+1行：第i+1行有一个整数E_i<br/>
<br/>
<br/>
</p></div>

# Output

<div class="content"><p><br/>
* 第一行：一个值，表示FJ可以得到的最大的效率值。<br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
<br/>
输入解释：<br/>
<br/>
FJ有5只奶牛，他们的效率为1，2，3，4，5。他们希望选取效率总和最大的奶牛，但是<br/>
他不能选取超过2只连续的奶牛<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
12<br/>
<br/>
FJ可以选择出了第三只以外的其他奶牛，总的效率为1+2+4+5=12。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

