
# Description

<div class="content"><div>我们称一个数列为一个好的k-d数列，当且仅当我们在其中加上最多k个</div>
<div>数之后，数列排序后为一个公差为d的等差数列。</div>
<div>你手上有一个由n个整数组成的数列a。你的任务是找到它的最长连续子</div>
<div>串，使得满足子串为好的k-d数列。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个用空格隔开的整数n,k,d（1&lt;=n&lt;=2*10^5;0&lt;=k&lt;=</div>
<div>2*10^5;0&lt;=d&lt;=10^9）。第二行包含n个空格隔开的整数：a1,a2,...,an（-10^9&lt;=ai&lt;=10^9）表示数列a。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出两个用空格隔开的整数L,r（1&lt;=L&lt;=r&lt;=n），表示数列a_L,a_L+1,...,</div>
<div>ar是好k-d数列的子串中最长的。</div>
<div>如果有多个最优答案，输出那个L值最小的。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 1 2<br/>
4 3 2 8 6 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 5<br/>
//第一个测试样例的答案为包括数字 2，8，6 的子串——在加入数字 4 并且<br/>
排序之后，它变成了数列 2，4，6，8——公差为 2 的等差数列。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

