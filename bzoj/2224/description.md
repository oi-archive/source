
# Description

<div class="content">对于正整数集合K, 非零十进制数字p, q被称作K-等价当且仅当以下条件成立:对于所有n∈K, 如果将n中的数字p替换成数字q, 或者将n中的数字q替换成p, 得到的新数字依然属于集合K.

例如, K是所有能被3整除的数构成的集合, 那么数字1, 4, 7是K-等价的.

可以看到, K-等价是一个等价关系(它满足自反性, 对称性和传递性).

给定一个有限集合K, 你的任务是找到数字1到数字9的等价类(即将[1,9]划分为若干个不相交的子集, 使得每个子集中的元素两两K-等价, 且任意两个属于不同集合的元素不K-等价).

</div>

# Input

<div class="content">第一行为整数n, 接下来有n行, 每行两个整数Li, Ri, 代表区间[Li, Ri]属于集合K. 0&lt;=Li&lt;=Ri&lt;=1018, 且对于i&gt;=2, Li&gt;Ri-1.

</div>

# Output

<div class="content">输出[1,9]的等价类. 每个等价类用一串递增的数字表示, 按照字典序输出.
</div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
1 566<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1234<br/>
5<br/>
6<br/>
789<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Neerc2010">Neerc2010</a></p></div>

