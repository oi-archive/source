
# Description

<div class="content"><p>FJ has purchased N (1 &lt;= N &lt;= 2000) yummy treats for the cows who get money for giving vast amounts of milk. FJ sells one treat per day and wants to maximize the money he receives over a given period time.  The treats are interesting for many reasons:   * The treats are numbered 1..N and stored sequentially in single     file in a long box that is open at both ends. On any day, FJ     can retrieve one treat from either end of his stash of treats.   * Like fine wines and delicious cheeses, the treats improve with     age and command greater prices.   * The treats are not uniform: some are better and have higher     intrinsic value. Treat i has value v(i) (1 &lt;= v(i) &lt;= 1000).   * Cows pay more for treats that have aged longer: a cow will     pay v(i)*a for a treat of age a.  Given the values v(i) of each of the treats lined up in order of the index i in their box, what is the greatest value FJ can receive for them if he orders their sale optimally?  The first treat is sold on day 1 and has age a=1. Each subsequent day increases the age by 1.</p>
<p><span style="font-size: medium; font-family: arial, verdana, helvetica, sans-serif; ">约翰经常给产奶量高的奶牛发特殊津贴，于是很快奶牛们拥有了大笔不知该怎么花的钱．为</span><span style="font-size: medium; font-family: arial, verdana, helvetica, sans-serif; ">此，约翰购置了N(1≤N≤2000)份美味的零食来卖给奶牛们．每天约翰售出一份零食．当然约翰</span><span style="font-size: medium; font-family: arial, verdana, helvetica, sans-serif; ">希望这些零食全部售出后能得到最大的收益．这些零食有以下这些有趣的特性：</span></p>
<div style="font-family: arial, verdana, helvetica, sans-serif; font-size: 14px; "><span style="font-size: medium; ">•零食按照1．．N编号，它们被排成一列放在一个很长的盒子里．盒子的两端都有开口，约翰每</span></div>
<div style="font-family: arial, verdana, helvetica, sans-serif; font-size: 14px; "><span style="font-size: medium; ">  天可以从盒子的任一端取出最外面的一个．</span></div>
<div style="font-family: arial, verdana, helvetica, sans-serif; font-size: 14px; "><span style="font-size: medium; ">•与美酒与好吃的奶酪相似，这些零食储存得越久就越好吃．当然，这样约翰就可以把它们卖</span><span style="font-size: medium; ">出更高的价钱．</span></div>
<div style="font-family: arial, verdana, helvetica, sans-serif; font-size: 14px; "><span style="font-size: medium; ">  •每份零食的初始价值不一定相同．约翰进货时，第i份零食的初始价值为Vi(1≤Vi≤1000)．</span></div>
<div style="font-family: arial, verdana, helvetica, sans-serif; font-size: 14px; "><span style="font-size: medium; ">  •第i份零食如果在被买进后的第a天出售，则它的售价是vi×a．</span></div>
<div style="font-family: arial, verdana, helvetica, sans-serif; font-size: 14px; "><span style="font-size: medium; ">  Vi的是从盒子顶端往下的第i份零食的初始价值．约翰告诉了你所有零食的初始价值，并</span><span style="font-size: medium; ">希望你能帮他计算一下，在这些零食全被卖出后，他最多能得到多少钱．</span></div>
<p></p></div>

# Input

<div class="content"><p>* Line 1: A single integer,</p>
<p>N  * Lines 2..N+1: Line i+1 contains the value of treat v(i)</p></div>

# Output

<div class="content"><p>* Line 1: The maximum revenue FJ can achieve by selling the treats</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1<br/>
3<br/>
1<br/>
5<br/>
2<br/>
<br/>
Five treats. On the first day FJ can sell either treat #1 (value 1) or<br/>
treat #5 (value 2).<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">43<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
FJ sells the treats (values 1, 3, 1, 5, 2) in the following order<br/>
of indices: 1, 5, 2, 3, 4, making 1x1 + 2x2 + 3x3 + 4x1 + 5x5 = 43.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

