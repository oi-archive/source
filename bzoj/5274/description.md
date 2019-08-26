
# Description

<div class="content"><div>首先我们定义两个多重集A和B的大小关系，找到最小的整数x使得在两个多重集中出现次数不同，然后整数x出现次</div>
<div>数大的多重集更小。如果这样的x不存在，那么相等。</div>
<div>比如{1,2,3}&lt;{1,3,3,5}，{1,1,4,4}&lt;{1,1,4}。</div>
<div>给你一个长为n的序列，序列中每个数字在1到n之间。</div>
<div>对于任意一个区间[l,r]，这里面的数字a_l,a_{l+1},…,a_r会形成一个多重集，一共形成n*(n+1)/2个多重集。</div>
<div>现在请输出这些多重集中第p小的到第q小的多重集对应的区间是什么</div>
<div>如果两个多重集一样大，那么我们认为对应的区间的左端点较小的更小。</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个正整数n,p,q</div>
<div>接下来一行n个1到n之间的整数，表示这个序列，序列下标从1开始标号。</div>
<div>n&lt;=100000,1&lt;=p&lt;=q&lt;=n*(n+1)/2且q&lt;=p+100000</div>
<p></p></div>

# Output

<div class="content"><div>输出q-p+1行，每行两个正整数表示多重集对应的区间。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 10 13<br/>
1 2 1 3 5 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 3<br/>
3 5<br/>
4 6<br/>
3 4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

