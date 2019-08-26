
# Description

<div class="content"><div>维护一个长度为N的序列a，现在有三种操作：</div>
<div>1）给出参数U,V,C，将a[U],a[U+1],...,a[V-1],a[V]都赋值为C。</div>
<div>2）给出参数U,V,C，对于区间[U,V]里的每个数i，将a[i]赋值为max(a[i]+C,0)。</div>
<div>3）给出参数U,V，输出a[U],a[U+1],...,a[V-1],a[V]里值为0的数字个数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数N,M(1&lt;=N,M&lt;=300000)，分别表示序列长度和操作个数。</div>
<div>第二行包含N个整数，其中第i个数表示a[i](0&lt;=a[i]&lt;=10^9)，描述序列的初始状态。</div>
<div>接下来M行描述M个操作，保证1&lt;=U&lt;=V&lt;=N，对于操作1，0&lt;=C&lt;=10^9，对于操作2，|C|&lt;=10^9。</div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，每行一个整数，依次回答每个操作3的问题。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
6 4 6 6 4 <br/>
2 1 5 -5<br/>
1 3 4 4<br/>
3 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p>2016.1.1新加数据</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

