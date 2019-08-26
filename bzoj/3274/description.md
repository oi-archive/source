
# Description

<div class="content"><div>有n个排成一圈的格子，并且已知正整数k和m，你需要往每个格子中填入一个大于等于k的正整数。将相邻的一些格</div>
<div>子（或一个单独的格子）中的数加起来，可以产生一个新的数。假设使用格子中的数可以产生出m,m+1,…i，但不</div>
<div>能产生i+1。求出往格子中填入哪些数，可以使得i尽量大。</div></div>

# Input

<div class="content"><div>三行，每行一个整数分别为n,m,k。（k&lt;=m）</div>
<div>n&lt;=6，k&lt;=m&lt;=20</div></div>

# Output

<div class="content"><div>第一行一个正整数，表示最大的i</div>
<div>下面若干行，每行为一个使i最大的填数方案，接照字典序列升序排列。</div>
<div>每行N个正整数a1,a2....an,表示依次向格子填 入的数，</div>
<div>其中a1是N个数中最小的数。</div>
<div>注意(1,1,2,3),(1,3,2,1),(1,2,3,1),(1,1,3,2)被认为是不同的方案，都要输出。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">21<br/>
1  3 10 2 5<br/>
1  5 2 10 3<br/>
2  4 9 3 5<br/>
2  5 3 9 4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

