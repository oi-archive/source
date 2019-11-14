
# Description

<div class="content"><p><span style="font-size: medium">农夫JOHN准备把他的 N（1 &lt;= N &lt;= 10,000）头牛排队以便于行动。因为脾气大的牛有可能会捣乱，JOHN想把牛按脾气的大小排序。每一头牛的脾气都是一个在1到100，000之间的整数并且没有两头牛的脾气值相同。在排序过程中，JOHN 可以交换任意两头牛的位置。因为脾气大的牛不好移动，JOHN需要X+Y秒来交换脾气值为X和Y的两头牛。 请帮JOHN计算把所有牛排好序的最短时间。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行： 一个数， N。</span></p>
<p><span style="font-size: medium">第2~N+1行： 每行一个数，第i+1行是第i头牛的脾气值。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第1行： 一个数，把所有牛排好序的最短时间。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2<br/>
3<br/>
1<br/>
<br/>
输入解释：<br/>
<br/>
队列里有三头牛，脾气分别为 2，3， 1。<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
输出解释：<br/>
2 3 1 : 初始序列<br/>
2 1 3 : 交换脾气为3和1的牛(时间=1+3=4). <br/>
1 2 3 : 交换脾气为1和2的牛(时间=2+1=3). <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

