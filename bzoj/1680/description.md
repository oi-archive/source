
# Description

<div class="content"><p>The cows have purchased a yogurt factory that makes world-famous Yucky Yogurt. Over the next N (1 &lt;= N &lt;= 10,000) weeks, the price of milk and labor will fluctuate weekly such that it will cost the company C_i (1 &lt;= C_i &lt;= 5,000) cents to produce one unit of yogurt in week i.  Yucky&#39;s factory, being well-designed, can produce arbitrarily many units of yogurt each week.  Yucky Yogurt owns a warehouse that can store unused yogurt at a constant fee of S (1 &lt;= S &lt;= 100) cents per unit of yogurt per week. Fortuitously, yogurt does not spoil.  Yucky Yogurt&#39;s warehouse is enormous, so it can hold arbitrarily many units of yogurt.  Yucky wants to find a way to make weekly deliveries of Y_i (0 &lt;= Y_i &lt;= 10,000) units of yogurt to its clientele (Y_i is the delivery quantity in week i). Help Yucky minimize its costs over the entire N-week period. Yogurt produced in week i, as well as any yogurt already in storage, can be used to meet Yucky&#39;s demand for that week.</p>
<p></p>
<p>吨酸奶。酸奶的生产受到很多因素的影响，所以每个月的生产成本是变化的，其中第 i 个月的成本是</p>
<p>每吨 Ci 元。</p>
<p>奶牛可以提前里把酸奶做好，存在仓库里，等需要的时候再拿出来卖。存储在仓库里的酸奶，每</p>
<p>吨酸奶存放一个月需要支付 S 元的维护费用，存放的时间可以任意长。假设工厂的产量是无限的，存</p>
<p>储酸奶的仓库也是无限大的。请问为了满足订单的需要，奶牛生产这些酸奶最少要花多少钱？</p></div>

# Input

<div class="content"><p>* Line 1: Two space-separated integers, N and S.</p>
<p> * Lines 2..N+1: Line i+1 contains two space-separated integers: C_i         and Y_i.</p>
<p></p>
<div>• 第一行：两个整数 N 和 S，1 ≤ N ≤ 10000, 1 ≤ S ≤ 100</div>
<div>• 第二行到第 N + 1 行：第 i + 1 行有两个整数 Ci 和 Ai，1 ≤ Ci ≤ 5000, 1 ≤ Ai ≤ 10000</div></div>

# Output

<div class="content"><p>* Line 1: Line 1 contains a single integer: the minimum total cost to         satisfy the yogurt schedule.  Note that the total might be too         large for a 32-bit integer.</p>
<p>• 单个整数：表示生产酸奶的最小总费用</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
88 200<br/>
89 400<br/>
97 300<br/>
91 500<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">126900<br/>
<br/>
OUTPUT DETAILS:<br/>
第一个月生产 200 吨酸奶；第二个月生产<br/>
700 吨酸奶，并存下 300 吨；第三个月不生产酸<br/>
奶；第三个月生产 500 吨</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

