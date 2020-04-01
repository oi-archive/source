
# Description

<div class="content"><div>火星上的一条商业街里按照商店的编号1，2 ，…，n ，依次排列着n个商店。商店里出售的琳琅满目的商品中，每种商品都用一个非负整数val来标价。每个商店每天都有可能进一些新商品，其标价可能与已有商品相同。 </div>
<div>火星人在这条商业街购物时，通常会逛这条商业街某一段路上的所有商店，譬如说商店编号在区间[L,R]中的商店，从中挑选1件自己最喜欢的商品。每个火星人对商品的喜好标准各不相同。通常每个火星人都有一个自己的喜好密码x。对每种标价为val的商品，喜好密码为x的火星人对这种商品的喜好程度与val异或x的值成正比。也就是说，val xor x的值越大，他就越喜欢该商品。每个火星人的购物卡在所有商店中只能购买最近d天内（含当天）进货的商品。另外，每个商店都有一种特殊商品不受进货日期限制，每位火星人在任何时刻都可以选择该特殊商品。每个商店中每种商品都能保证供应，不存在商品缺货的问题。 </div>
<div>对于给定的按时间顺序排列的事件，计算每个购物的火星人的在本次购物活动中最喜欢的商品，即输出val xor x的最大值。这里所说的按时间顺序排列的事件是指以下2种事件： </div>
<div>事件0，用三个整数0,s,v，表示编号为s的商店在当日新进一种标价为v 的商品。 </div>
<div>事件1，用5个整数1,L,R,x,d，表示一位火星人当日在编号为L到R的商店购买d天内的商品，该火星人的喜好密码为x。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行中给出2个正整数n,m，分别表示商店总数和事件总数。 </div>
<div>
<div>第2行中有n个整数，第i个整数表示商店i的特殊商品标价。 </div>
<div>接下来的m行，每行表示1个事件。每天的事件按照先事件0，后事件1的顺序排列。 </div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>将计算出的每个事件1的val xor x的最大值依次输出。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1 2 3 4<br/>
1 1 4 1 0<br/>
0 1 4<br/>
0 1 3<br/>
1 1 1 1 0<br/>
1 1 1 1 1<br/>
1 1 2 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
0<br/>
2<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p><div>n, m &lt;= 100000</div><br/>
<div>数据中，价格不大于<span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.333333015441895px;">100000</span></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

