
# Description

<div class="content"><p>有n家洗车店从左往右排成一排，每家店都有一个正整数价格p[i]。<br/>
有m个人要来消费，第i个人会驶过第a[i]个开始一直到第b[i]个洗车店，且会选择这些店中最便宜的一个进行一次消费。但是如果这个最便宜的价格大于c[i]，那么这个人就不洗车了。<br/>
请给每家店指定一个价格，使得所有人花的钱的总和最大。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m(1&lt;=n&lt;=50，1&lt;=m&lt;=4000)。<br/>
接下来m行，每行包含三个正整数a[i],b[i],c[i](1&lt;=a[i]&lt;=b[i]&lt;=n，1&lt;=c[i]&lt;=500000)</p></div>

# Output

<div class="content"><p>第一行输出一个正整数，即消费总额的最大值。<br/>
第二行输出n个正整数，依次表示每家洗车店的价格p[i]，要求1&lt;=p[i]&lt;=500000。<br/>
若有多组最优解，输出任意一组。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7 5<br/>
1 4 7<br/>
3 7 13<br/>
5 6 20<br/>
6 7 1<br/>
1 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">43<br/>
5 5 13 13 20 20 13</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

