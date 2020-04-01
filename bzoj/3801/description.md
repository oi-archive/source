
# Description

<div class="content"><p style="text-align: left;">在一个名字叫做Baka⑨的国家里有M个正在工作的货币兑换站。每个兑换站专门兑换N种货币中的两种货币。可以有多间兑换站都兑换同样的两种货币，不过每间兑换站都有它们自己的汇率。A对B的汇率就是，你给1A能得到多少B。另外每个兑换站都会从你给的金钱中收取一定的手续费。例子：如果你想把100 US 换成 RUSSIAN RUBLES，兑换站的汇率是29.75，而手续费是0.39，那么你就能得到（100－0.39）*29.75= 2963.3975 RUR。 </p>
<p>有一天，一个叫做No Moral的人拿着一些某个币种的货币跑到Baka⑨国买带锁的赛钱箱。买赛钱箱要用到别国货币，要换到这种货币中途还得各种换其他国的货币，比如BirdBrain⑥国、SoDeSuGa⑩国、PAD⒃国、Bilibili⒆国之类的。于是她经过一番复杂的兑换之后终于买到东西又兑换回来，结果发现买完东西之后，她的钱反而变多了！ </p>
<p>怀着要把自己的赛钱刷上10W的夙愿，No Moral请她的好姬友Dog Leg Aya调查了Baka⑨国中所有的货币站当前的兑换币种、汇率和手续费（可能和之前已经不一样了，所以不知道能不能刷钱）。No Moral想要知道，现在她还能不能无限刷钱。注意，刷钱要把钱刷回原来的币种。 </p>
<pre></pre>
<p></p></div>

# Input

<div class="content"><p>第一行输入N（持有的货币），M（兑换站的数量），S（No Moral持有的货币种类），V（No Moral持有的货币数量）。1&lt;=S&lt;=N&lt;=100，1&lt;=M&lt;=100，V是实数，0&lt;=V&lt;=1000。 </p>
<p>以下的M行每行输入6个数，为该站点可兑换的两个币种、第一个币种对第二个币种的兑换率和手续费、第二个币种对第一个币种的兑换率和手续费。每个兑换站的汇率和手续费都是实数，保留最多两位小数。0.01&lt;=汇率&lt;=100，0&lt;=手续费&lt;=100。 </p>
<p></p></div>

# Output

<div class="content"><div>如果No Moral能无限刷钱，输出YES，否则输出NO。 </div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 1 20.0<br/>
1 2 1.00 1.00 1.00 1.00<br/>
2 3 1.10 1.00 1.10 1.00<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

