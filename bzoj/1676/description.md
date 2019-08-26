
# Description

<div class="content"><p><span style="font-size: medium">Farmer John is trying to figure out when his last shipment of feed arrived. Starting with an empty grain bin, he ordered and received F1 (1 &lt;= F1 &lt;= 1,000,000) kilograms of feed. Regrettably, he is not certain exactly when the feed arrived. Of the F1 kilograms, F2 (1 &lt;= F2 &lt;= F1) kilograms of feed remain on day D (1 &lt;= D &lt;= 2,000). He must determine the most recent day that his shipment could have arrived. Each of his C (1 &lt;= C &lt;= 100) cows eats exactly 1 kilogram of feed each day. For various reasons, cows arrive on a certain day and depart on another, so two days might have very different feed consumption. The input data tells which days each cow was present. Every cow ate feed from Farmer John&#39;s bin on the day she arrived and also on the day she left. Given that today is day D, determine the minimum number of days that must have passed since his last shipment. The cows have already eaten today, and the shipment arrived before the cows had eaten. </span></p>
<div><span style="font-size: medium">约翰想知道上一船饲料是什么时候运到的．在饲料运到之前，他的牛正好把仓库里原来的饲料全吃光了．    他收到运来的F1(1≤Fi≤1000000)千克饲料．遗憾的是，他已经不记得这是哪一天的事情了．到第D(1≤D≤2000)天为止，仓库里还剩下F2（1≤F2≤Fi）千克饲料．</span></div>
<div><span style="font-size: medium">    约翰养了C(1≤C≤100)头牛，每头牛每天都吃掉恰好1千克饲料．由于不同的原因，牛们从某一天开始在仓库吃饲料，又在某一天离开仓库，所以不同的两天可能会有差距很大的饲料消耗量．每头牛在来的那天和离开的那天都在仓库吃饲料．    给出今天的日期D，写一个程序，判断饲料最近一次运到是在什么时候．今天牛们已经吃过饲料了，并且饲料运到的那天牛们还没有吃过饲料．</span></div>
<div></div></div>

# Input

<div class="content"><p>* Line 1: Four space-separated integers: C, F1, F2, and D * Lines 2..C+1: Line i+1 contains two space-separated integers describing the presence of a cow. The first integer tells the first day the cow was on the farm; the second tells the final day of the cow&#39;s presence. Each day is in the range 1..2,000.</p>
<div><span style="font-size: medium">    第1行：四个整数C，F1，F2，D，用空格隔开．</span></div>
<div><span style="font-size: medium">    第2到C+1行：每行是用空格隔开的两个数字，分别表示一头牛来仓库吃饲料的时间和离开</span><span style="font-size: medium">的时间．</span></div>
<div></div></div>

# Output

<div class="content"><p><span style="font-size: medium">The last day that the shipment might have arrived, an integer that will always be positive. </span></p>
<div><span style="font-size: medium">    一个正整数，即上一船饲料运到的时间．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 14 4 10<br/>
1 9<br/>
5 8<br/>
8 12<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The shipment was 14 kilograms of feed, and Farmer John has 4 kilograms<br/>
left.  He had three cows that ate feed for some amount of time in<br/>
the last 10 days.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
    上一次运来了14千克饲料，现在饲料还剩下4千克．最近10天里．有3头牛来吃过饲料．<br/>
  约翰在第6天收到14千克饲料，当天吃掉2千克，第7天吃掉2千克，第8天吃掉3千克，第9天吃掉2千克，第10天吃掉1千克，正好还剩4千克<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

