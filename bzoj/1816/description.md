
# Description

<div class="content">你有n种牌，第i种牌的数目为ci。另外有一种特殊的牌：joker，它的数目是m。你可以用每种牌各一张来组成一套牌，也可以用一张joker和除了某一种牌以外的其他牌各一张组成1套牌。比如，当n=3时，一共有4种合法的套牌：{1,2,3}, {J,2,3}, {1,J,3}, {1,2,J}。
给出n, m和ci，你的任务是组成尽量多的套牌。每张牌最多只能用在一副套牌里（可以有牌不使用）。

</div>

# Input

<div class="content">第一行包含两个整数n, m，即牌的种数和joker的个数。第二行包含n个整数ci，即每种牌的张数。

</div>

# Output

<div class="content">输出仅一个整数，即最多组成的套牌数目。

</div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 2 3	</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
样例解释<br/>
输入数据表明：一共有1个1，2个2，3个3，4个joker。最多可以组成三副套牌：{1,J,3}, {J,2,3}, {J,2,3}，joker还剩一个，其余牌全部用完。<br/>
<br/>
数据范围<br/>
50%的数据满足：2 &lt; = n &lt; = 5, 0 &lt; = m &lt; = 10^ 6, 0&lt; = ci &lt; = 200<br/>
100%的数据满足：2 &lt; = n &lt; = 50, 0 &lt; = m, ci &lt; = 500,000,000。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

