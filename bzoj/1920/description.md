
# Description

<div class="content"><img border="0" src="/source/bzoj/1920/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MjBfMS5qcGc=.jpg"/> </div>

# Input

<div class="content"><img border="0" src="/source/bzoj/1920/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MjBfMi5qcGc=.jpg"/> </div>

# Output

<div class="content">仅包含一个非负整数，表示公司的最小总耗费。</div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
3 2 1 2 <br/>
2 5 2 2 <br/>
5 1 5 5 <br/>
1 2 1  <br/>
5 3 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">30</span></div>

# Hint

<div class="content"><p>第一个季度生产 2件产品，第二个季度生产5 件产品，第三个季度不生产产<br/>
品，第四个季度生产 1 件产品，成本为 2 * 5 + 5 * 1 + 0 * 5 + 1 * 5 = 20。 <br/>
因为第一个季度最多只能生产 2 件产品，无法满足 3 件的订购量，因此将 1<br/>
件产品的订购量推迟到第二个季度，赔偿给用户的损失费为 5。 <br/>
第二个季度由于第一个季度推迟了一件产品的订购需求， 因而订购量变为 3。<br/>
该季度生产了5件产品， 剩下的2件保存下来。 第三个季度直接销售库存的产品，<br/>
再多出来的 1 件产品继续储存到第四个季度，加上第四个季度生产了 1 件产品，<br/>
因此满足了所有订单需求。总的储存费用为 2 * 2 + 1 * 1 = 5。 <br/>
总的费用为 20 + 5 + 5 = 30。 <br/>
 <br/>
对于 30%的数据，N൑&lt; = 1,000。 <br/>
对于 100%的数据，1  &lt; =൑N &lt; =൑ 100,000，1&lt; =൑Di, Ui, Pi, Mi,Ci &lt; =൑ 10,000。 <br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

