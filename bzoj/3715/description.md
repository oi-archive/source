
# Description

<div class="content"><p>Byteasar公司专门外包生产带有镜子的衣柜。<br/>
刚刚举行的招标会上，有n个工厂参加竞标。所有镜子都是长方形的，每个工厂能够制造的镜子都有其各自的最大、最小宽度和最大、最小高度。镜子不可以旋转。<br/>
如果存在某家工厂满足这样的条件：其他所有工厂能够制造的镜子，它都能够制造。那么这家工厂显然会胜出。若不存在，评判工作将会遇到麻烦。Byteasar想知道，是否存在某家工厂符合上述条件。</p></div>

# Input

<div class="content"><p>第一行有一个整数t(1&lt;=t&lt;=10)，表示测试数据数量。<br/>
对于每一组测试数据，第一行有一个整数n(2&lt;=n&lt;=100000)。接下来n行，每行有四个整数w1,w2,h1,h2(1&lt;=w1&lt;=w2&lt;=10^9,1&lt;=h1&lt;=h2&lt;=10^9)，表示这家工厂能够制造的镜子的宽度w、高度h需要满足w1&lt;=w&lt;=w2,h1&lt;=h&lt;=h2。</p></div>

# Output

<div class="content"><p>输出共有t行，每行为TAK(是)或NIE(否)，表示是否存在某家工厂符合条件。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3<br/>
2 3 3 5<br/>
1 4 2 6<br/>
1 3 4 6<br/>
3<br/>
1 5 1 3<br/>
2 4 1 3<br/>
3 4 2 5<br/>
4<br/>
1 2 1 10<br/>
1 2 3 8<br/>
2 2 7 10<br/>
1 2 1 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE<br/>
TAK<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

