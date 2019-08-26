
# Description

<div class="content"><div>n个人（编号为1~n）围着圆桌坐成一圈。座位相邻的两个人，其编号之差的绝对值不可以超过p。</div>
<div>他们之中有些人不喜欢别人。如果a不喜欢b，那么b不能坐在a右边的那一个位置上。</div>
<div>现在，假设第n个人的座位已经固定，要给剩下的人安排座位，共有几种合法方案？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个整数n,k,p(1&lt;=n&lt;=1000000,0&lt;=k&lt;=100000,0&lt;=p&lt;=3)。</div>
<div>接下来k行，每行含两个整数a[i],b[i](1 &lt;= a[i],b[i] &lt;= n, a[i]≠b[i])，表示a[i]不喜欢b[i]。同一组a[i],b[i]不会重复输入。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数，表示方案数模10^9+7后的值。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2 3<br/>
1 3<br/>
5 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
样例解释：<br/>
合法方案有53124,53142,52143,53412,52314,53214。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

