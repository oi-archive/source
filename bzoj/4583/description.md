
# Description

<div class="content"><div>商店出售3种颜色的球，分别为红、绿、蓝。城市里有n个商店，第i个商店在第First_i天开始营业，连续营业Red_</div>
<div>i+Green_i+Blue_i天，每个商店每天只能出售一种颜色的球。每天最多有两个商店同时营业。如果同一天内有两个</div>
<div>商店同时营业，那么这两个商店必须出售相同颜色的球。求不同的出售方案数（对1,000,000,007取模）。两种方</div>
<div>案不同，当且仅当某一天某一个商店出售的球的颜色不同。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行只包含一个整数n，表示商店的个数。</div>
<div>接下来一行有n个数，第i个数表示First_i。</div>
<div>接下来一行有n个数，第i个数表示Red_i。</div>
<div>接下来一行有n个数，第i个数表示Green_i。</div>
<div>接下来一行有n个数，第i个数表示Blue_i。</div>
<div>
<div>1≤n≤50</div>
<div>1≤First_i≤500</div>
<div>0≤Red_i, Green_i, Blue_i≤100</div>
<div>0&lt;Red_i + Green_i + Blue_i</div>
<div>First_i + Red_i + Green_i + Blue_i - 1≤500</div>
<div>保证每天最多有两个商店同时营业。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出仅包含一个数，表示对1,000,000,007取模后的方案数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【Input1】<br/>
1<br/>
1<br/>
1<br/>
1<br/>
1<br/>
<br/>
【Input2】<br/>
2<br/>
1 2<br/>
1 1<br/>
1 1<br/>
1 1<br/>
<br/>
【Input3】<br/>
4<br/>
2 2 70 159<br/>
100 20 21 52<br/>
100 20 29 45<br/>
100 22 39 30</span></div>

# Sample Output

<div class="content"><span class="sampledata">【Output1】<br/>
6<br/>
<br/>
【Output2】<br/>
6<br/>
<br/>
【Output3】<br/>
139586270</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=SRM601 WinterAndShopping By 908997989">SRM601 WinterAndShopping By 908997989</a></p></div>

