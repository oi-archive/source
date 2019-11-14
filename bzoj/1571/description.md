
# Description

<div class="content"><p><span style="font-size: medium">Farmer John 想要带着 Bessie 一起在科罗拉多州一起滑雪。很不幸，Bessie滑雪技术并不精湛。 Bessie了解到，在滑雪场里，每天会提供S(0&lt;=S&lt;=100)门滑雪课。第i节课始于M_i(1&lt;=M_i&lt;=10000),上的时间为L_i(1&lt;=L_i&lt;=10000)。上完第i节课后，Bessie的滑雪能力会变成A_i(1&lt;=A_i&lt;=100). 注意：这个能力是绝对的，不是能力的增长值。 Bessie买了一张地图，地图上显示了N(1 &lt;= N &lt;= 10,000)个可供滑雪的斜坡，从第i个斜坡的顶端滑至底部所需的时长D_i(1&lt;=D_i&lt;=10000)，以及每个斜坡所需要的滑雪能力C_i(1&lt;=C_i&lt;=100)，以保证滑雪的安全性。Bessie的能力必须大于等于这个等级，以使得她能够安全滑下。 Bessie可以用她的时间来滑雪，上课，或者美美地喝上一杯可可汁，但是她必须在T(1&lt;=T&lt;=10000)时刻离开滑雪场。这意味着她必须在T时刻之前完成最后一次滑雪。 求Bessie在实现内最多可以完成多少次滑雪。这一天开始的时候，她的滑雪能力为1. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行：3个用空格隔开的整数：T, S, N。</span></p>
<p><span style="font-size: medium">第2~S+1行:第i+1行用3个空格隔开的整数来描述编号为i的滑雪课：M_i,L_i,A_i。</span></p>
<p><span style="font-size: medium">第S+2~S+N+1行：</span></p>
<p><span style="font-size: medium">第S+i+1行用2个空格隔开的整数来描述第i个滑雪坡：C_i,D_i。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个整数，表示Bessie在时间限制内最多可以完成多少次滑雪。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 1 2<br/>
3 2 5<br/>
4 1<br/>
1 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">滑第二个滑雪坡1次，然后上课，接着滑5次第一个滑雪坡。 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

