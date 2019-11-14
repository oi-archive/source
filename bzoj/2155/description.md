
# Description

<div class="content"><p>设sum(S) 表示集合S 中所有元素的和。如果对于S 的任意两个不相交子集A 和B，如果他们满足： sum(A) ̸ 不等于 sum(B) (1) if |A| &gt; |B| then sum(A) &gt; sum(B) (2) 则称S 是R 集合。现在我们假设有一个大小为N，元素互不相等的集合，已经满足了条件(2)，并且知道所有元素之间的大小关系。问最坏情况下最少需要几次比较才能确定它是不是R 集合。</p></div>

# Input

<div class="content"><p>输入的第一行包含一个整数N。</p></div>

# Output

<div class="content"><p>输出一个整数，表示最少比较次数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
[样例说明]<br/>
设这个4 元集的元素是a1 &lt; a2 &lt; a3 &lt; a4，那么我们只需要比较<br/>
sum(a1; a4) 和sum(a2; a3)。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>一共有20 个数据，对于第i (1 &lt;= i &lt;= 20) 个数据， N = i * 50。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

