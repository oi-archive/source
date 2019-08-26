
# Description

<div class="content"><div>一个餐厅在相继的n天里，每天需用的餐巾数不尽相同。假设第i天(i=1,2,...,n)需要ri块餐巾。餐厅可以在任意</div>
<div>时刻购买新的餐巾，每块餐巾的费用为P。使用过的旧餐巾，则需要经过清洗才能重新使用。把一块旧餐巾送到清</div>
<div>洗店A，需要等待m1天后才能拿到新餐巾，其费用为c1；把一块旧餐巾送到清洗店B，需要等待m2天后才能拿到新餐</div>
<div>巾，其费用为c2。例如，将一块第k天使用过的餐巾送到清洗店A清洗，则可以在第k+m1天使用。请为餐厅合理地安</div>
<div>排好n天中餐巾使用计划，使总的花费最小。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，包含六个个正整数n,m1,m2,c1,c2,p</div>
<div>接下来输入n行，每行包含一个正整数ri。</div>
<div>1≤n≤200000，1≤m1,m2≤n，1≤c1,c2,p≤100，1≤ri≤100</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行，包含一个正整数，表示最小的总花费</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1 2 2 1 3<br/>
8<br/>
2<br/>
1<br/>
6</span></div>

# Sample Output

<div class="content"><span class="sampledata">35<br/>
第1天：买8块餐巾，花费24。送2块餐巾去清洗店A，6块餐巾去清洗店B。<br/>
第2天：取回2块清洗店A的餐巾，花费4。送1块餐巾去清洗店B。<br/>
第3天：取回6块清洗店B的餐巾，花费6。<br/>
第4天：取回1块清洗店B的餐巾，花费1。这样就用了最少的钱。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

