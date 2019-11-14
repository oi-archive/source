
# Description

<div class="content"><p><span style="font-size: medium">As a reward for record milk production, Farmer John has decided to start paying Bessie the cow a small weekly allowance. FJ has a set of coins in N (1 &lt;= N &lt;= 20) different denominations, where each denomination of coin evenly divides the next-larger denomination (e.g., 1 cent coins, 5 cent coins, 10 cent coins, and 50 cent coins). Using the given set of coins, he would like to pay Bessie at least some given amount of money C (1 &lt;= C &lt;= 100,000,000) every week. Please help him compute the maximum number of weeks he can pay Bessie. </span></p>
<div><span style="font-size: medium">作为对勤勤恳恳工作的贝茜的奖励，约翰已经决定开始支付贝茜一个小的每周津贴．</span><span style="font-size: medium">  约翰有n(1≤N≤20)种币值的硬币，面值小的硬币总能整除面值较大的硬币．比如说，币值有如下几种：1美分，5美分，10美分，50美分…．．</span></div>
<div><span style="font-size: medium">    利用给定的这些硬币，他将要每周付给贝茜一定金额的津贴C(1≤C≤10^8)．</span></div>
<div><span style="font-size: medium">    请帮他计算出他最多能给贝茜发几周的津贴．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：2个用空格隔开的整数n和C.</span></div>
<div><span style="font-size: medium">    第2到n+1行：每行两个整数表示一种币值的硬币．第一个整数V(I≤y≤10^8)，表示币值．</span></div>
<div><span style="font-size: medium">第二个整数B(1≤B≤10^6)，表示约翰拥有的这种硬币的个数．</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    一个整数，表示约翰付给贝茜津贴得最多的周数．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">    3  6<br/>
    10  1<br/>
    1  1 00<br/>
    5  1 20<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">   111<br/>
样例说明<br/>
    约翰想要每周付给贝茜6美分．他有1个10美分的硬币、100个1美分的硬币、120个5美分的硬币．约翰可以第一周付给贝茜一个10美分的硬币，接着的10周每周付给贝茜2个5芙分硬币，接下来的100周每周付给贝茜一个1美分的硬币和1个5美分的硬币．共计111周．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

