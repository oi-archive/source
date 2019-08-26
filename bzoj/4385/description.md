
# Description

<div class="content"><p>给定一个长度为n的序列，你有一次机会选中一段连续的长度不超过d的区间，将里面所有数字全部修改为0。<br/>
请找到最长的一段连续区间，使得该区间内所有数字之和不超过p。</p></div>

# Input

<div class="content"><p>第一行包含三个整数n,p,d(1&lt;=d&lt;=n&lt;=2000000，0&lt;=p&lt;=10^16)。<br/>
第二行包含n个正整数，依次表示序列中每个数w[i](1&lt;=w[i]&lt;=10^9)。</p></div>

# Output

<div class="content"><p>包含一行一个正整数，即修改后能找到的最长的符合条件的区间的长度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">9 7 2<br/>
3 4 1 9 4 1 7 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p>将第4个和第5个数修改为0，然后可以选出区间[2,6]，总和为4+1+0+0+1=6。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

