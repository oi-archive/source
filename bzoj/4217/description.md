
# Description

<div class="content"><div>定义一个子集的和为该子集中所有数的和，特别的，定义空集的和为0。</div>
<div>已知一个非空多重整数集合S以及其每个子集的和，构造出原集合S，如果有多个可能的S，那么输出将S内所有元素排序后，字典序最小的一个。数据保证有解。 </div>
<p></p></div>

# Input

<div class="content"><div>第一行有一个正整数T，表示数据组数。</div>
<div>每组数据第一行有一个正整数n，接下来2行，第一行n个整数Si，第二行n个整数Pi，每个数对(Si,Pi)表示和为Si的子集有Pi个。</div>
<p></p></div>

# Output

<div class="content"><div>对每组数据输出一行Case #数据编号:，接着按升序输出S中的数，可参考样例输出。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
8<br/>
0 1 2 3 4 5 6 7<br/>
1 1 1 1 1 1 1 1<br/>
4<br/>
0 1 3 4<br/>
4 4 4 4<br/>
5<br/>
-2 -1 0 1 2<br/>
1 2 2 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 1 2 4<br/>
Case #2: 0 0 1 3<br/>
Case #3: -2 1 1<br/>
<br/>
【样例解释】<br/>
    对第三组数据，多重集-1 -1 2同样可能，但是-2 1 1的字典序更小，所以应输出-2 1 1。</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，S的大小不超过60，n&lt;=10000，T&lt;=100，|Si|&lt;=10^10，Pi&gt;=1。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

