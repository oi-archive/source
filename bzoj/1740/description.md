
# Description

<div class="content"><p><span style="font-size: medium">The cows have purchased a yogurt factory that makes world-famous Yucky Yogurt. Over the next N (1 &lt;= N &lt;= 10,000) weeks, the price of milk and labor will fluctuate weekly such that it will cost the company C_i (1 &lt;= C_i &lt;= 5,000) cents to produce one unit of yogurt in week i. Yucky&#39;s factory, being well-designed, can produce arbitrarily many units of yogurt each week. Yucky Yogurt owns a warehouse that can store unused yogurt at a constant fee of S (1 &lt;= S &lt;= 100) cents per unit of yogurt per week. Fortuitously, yogurt does not spoil. Yucky Yogurt&#39;s warehouse is enormous, so it can hold arbitrarily many units of yogurt. Yucky wants to find a way to make weekly deliveries of Y_i (0 &lt;= Y_i &lt;= 10,000) units of yogurt to its clientele (Y_i is the delivery quantity in week i). Help Yucky minimize its costs over the entire N-week period. Yogurt produced in week i, as well as any yogurt already in storage, can be used to meet Yucky&#39;s demand for that week. </span></p>
<div><span style="font-size: medium"> 牛们收购了一个奶酪工厂,接下来的N个星期里，牛奶价格和劳力价格不断起伏．第i周，生产一个单位奶酪需要Ci(1≤Ci≤5000)便士．工厂有一个货栈，保存一单位奶酪，每周需要S(1≤S≤100)便士，这个费用不会变化．货栈十分强大，可以存无限量的奶酪，而且保证它们不变质．工厂接到订单，在第i周需要交付Yi(0≤Yi≤104)单位的奶酪给委托人．第i周刚生产的奶酪，以及之前的存货，都可以作为产品交付．请帮牛们计算这段时间里完成任务的最小代价．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers, N and S. </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Line i+1 contains two space-separated integers: C_i and Y_i.</span></p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">    第1行输入两个整数N和S．接下来N行输入Ci和Yi．</span></div>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: Line 1 contains a single integer: the minimum total cost to satisfy the yogurt schedule. Note that the total might be too large for a 32-bit integer. </span></p>
<div><span style="font-size: medium">    输出最少的代价．注意，可能超过32位长整型．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
88 200<br/>
89 400<br/>
97 300<br/>
91 500<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">126900<br/>
<br/>
第1周生产200单位奶酪并全部交付；第2周生产700单位，交付400单位，有300单位；第3周交<br/>
付300单位存货．第4周生产并交付500单位．<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

