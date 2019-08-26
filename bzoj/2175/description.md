
# Description

<div class="content"><p><span style="font-size: medium">问题描述<br/>
欧洲杯将至，欧足联在欧洲杯之前宣布了一项决定：成立一个新的联赛——欧洲超级联赛，并将欧洲各豪门俱乐部加入该联赛。<br/>
众所周知，各联赛都将转播权卖给各电视台以盈利，欧洲超级联赛自然也不例外，可是问题也随之出现：不同的比赛激烈程度自然不同，例如国际米兰 与尤文图斯 ，曼联 与阿森纳 ，巴萨罗那 与皇家马德里 这样的比赛自然人人都愿意看，可是遇上了利物浦 与切尔西 这样的比赛球迷们就不高兴啦(至少作者会不高兴)<br/>
因此欧足联为每场比赛定了一个级别,以此来表示比赛的受欢迎程度。<br/>
然而，分级的方法却不只一种。例如，可以将所有比赛分为A，B，C共3种级别，也可以分成W（Wildness，野蛮型），T（Technic，技术型）共2种级别。<br/>
可是如果某轮联赛有多种级别的比赛，精明的电视台当然都会购买最激烈的比赛的转播权，这是欧足联的高官们所不愿看到的（因为联赛的盈利会因此减少），所以每轮联赛只能有同一种级别的比赛。<br/>
可挑剔的球迷希望：联赛不是循环的（即无法将联赛分为K（K为小于N的任意正整数）段并使这K段都相同），因为这样才不会引起他们的审美疲劳。<br/>
已知联赛共有N轮，第i种分级方法有Ri种级别的比赛，现在欧足联想知道在每种分级方法下有多少种安排联赛的方案（注：把某种方案顺移K（K&lt;=N）位后任然是同一种方案，例如,ABC和BCA，CAB为同一种方案，但ABC和ACB不是同一种方案）。为此，欧足联设下了奖品，谁能提供答案谁就能获得这份奖励。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"> 第一行两个数N，M分别表示有N轮联赛和M种分级方法。<br/>
 第二行M个数，第i个数为Ri，意义如题</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"> M行，每行一个数ansi表示第i种分级方法下的方案数。</span></p>
<p><span style="font-size: medium"><br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata"> 3 1<br/>
 3<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 8<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 在样例1中，8种方案分别为AAB，AAC，BBA，BBC，CCA，CCB，ABC，ACB。<br/><br/>
数据范围<br/><br/>
对于20%的数据，满足M&lt;=10<br/><br/>
 对于所有的数据，满足<br/><br/>
 N&lt;=1000<br/><br/>
M&lt;=100<br/><br/>
Ri&lt;=256 （1&lt;=i&lt;=M）</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

