
# Description

<div class="content"><div>给出一个长度为N的数列{a[n]}，1&lt;=a[i]&lt;=M(1&lt;=i&lt;=N)。 </div>
<div>现在问题是，对于1到M的每个整数d，有多少个不同的数列b[1], b[2], ..., b[N]，满足： </div>
<div>(1)1&lt;=b[i]&lt;=M(1&lt;=i&lt;=N)； </div>
<div>(2)gcd(b[1], b[2], ..., b[N])=d； </div>
<div>(3)恰好有K个位置i使得a[i]&lt;&gt;b[i](1&lt;=i&lt;=N) </div>
<div>注：gcd(x1,x2,...,xn)为x1, x2, ..., xn的最大公约数。 </div>
<div>输出答案对1,000,000,007取模的值。 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含3个整数，N，M，K。 </div>
<div>第二行包含N个整数：a[1], a[2], ..., a[N]。 </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出M个整数到一行，第i个整数为当d=i时满足条件的不同数列{b[n]}的数目mod 1,000,000,007的值。 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 3<br/>
3 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">7 1 0</span></div>

# Hint

<div class="content"><p></p><div>当d=1，{b[n]}可以为：(1, 1, 1), (1, 1, 2), (1, 2, 1), (1, 2, 2), (2, 1, 1), (2, 1, 2), (2, 2, 1)。 </div><br/>
<div>当d=2，{b[n]}可以为：(2, 2, 2)。 </div><br/>
<div>当d=3，因为{b[n]}必须要有k个数与{a[n]}不同，所以{b[n]}不能为(3, 3, 3)，满足条件的一个都没有。 </div><br/>
<div>对于100%的数据，1&lt;=N,M&lt;=300000, 1&lt;=K&lt;=N, 1&lt;=a[i]&lt;=M。 </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

