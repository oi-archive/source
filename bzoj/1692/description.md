
# Description

<div class="content"><p><span style="font-size: medium">FJ打算带他的N(1 &lt;= N &lt;= 30,000)头奶牛去参加一年一度的“全美农场主大奖赛”。在这场比赛中，每个参赛者都必须让他的奶牛排成一列，然后领她们从裁判席前依次走过。 今年，竞赛委员会在接受队伍报名时，采用了一种新的登记规则：他们把所有队伍中奶牛名字的首字母取出，按它们对应奶牛在队伍中的次序排成一列（比如说，如果FJ带去的奶牛依次为Bessie、Sylvia、Dora，登记人员就把这支队伍登记为BSD）。登记结束后，组委会将所有队伍的登记名称按字典序升序排列，就得到了他们的出场顺序。 FJ最近有一大堆事情，因此他不打算在这个比赛上浪费过多的时间，也就是说，他想尽可能早地出场。于是，他打算把奶牛们预先设计好的队型重新调整一下。 FJ的调整方法是这样的：每次，他在原来队列的首端或是尾端牵出一头奶牛，把她安排到新队列的尾部，然后对剩余的奶牛队列重复以上的操作，直到所有奶牛都被插到了新的队列里。这样得到的队列，就是FJ拉去登记的最终的奶牛队列。 接下来的事情就交给你了：对于给定的奶牛们的初始位置，计算出按照FJ的调整规则所可能得到的字典序最小的队列。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 一个整数：N </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1行仅有1个&#39;A&#39;..&#39;Z&#39;中的字母，表示队列中从前往后数第i 头奶牛名字的首字母</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1..??行: 输出FJ所能得到的字典序最小的队列。每行（除了最后一行）输 出恰好80个&#39;A&#39;..&#39;Z&#39;中的字母，表示新队列中每头奶牛姓名的首 字母 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
A<br/>
C<br/>
D<br/>
B<br/>
C<br/>
B<br/>
<br/>
输入说明:<br/>
<br/>
    FJ有6头顺次排好队的奶牛：ACDBCB<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">ABCBCD<br/>
<br/>
输出说明:<br/>
<br/>
 操作数   原队列     新队列<br/>
   #1     ACDBCB<br/>
   #2      CDBCB     A<br/>
   #3      CDBC      AB<br/>
   #4      CDB       ABC<br/>
   #5      CD        ABCB<br/>
   #6       D        ABCBC<br/>
   #7                ABCBCD<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

