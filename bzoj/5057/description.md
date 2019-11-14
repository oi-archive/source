
# Description

<div class="content"><div>有n(n&lt;=30000)个位置，q(q&lt;=30000)个操作,操作有两种。一. 1 l r a b 表示在第l个位置到第r个位置，每个位</div>
<div>置加入a到b之间的所有数，一开始所有位置为空。(1&lt;=l&lt;=r&lt;=n,1&lt;=a&lt;=b&lt;=n)二. 2 l r k 表示询问从第l个位置到</div>
<div>第r个位置，第k小的数是多少。(1&lt;=l&lt;=r&lt;=n,1&lt;=k&lt;=n*n*q,保证k合法)</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n和q。</div>
<div>接下来q行，每行为1 l r a b或2 l r k。</div>
<div>保证第一次操作为操作一。</div>
<div>测试数据均为随机产生。</div>
<p></p></div>

# Output

<div class="content"><div>输出每个询问的结果</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 14<br/>
1 1 2 1 2<br/>
2 1 2 1<br/>
2 1 2 2<br/>
2 1 2 3<br/>
2 1 2 4<br/>
1 2 2 2 2<br/>
2 1 2 1<br/>
2 1 2 2<br/>
2 1 2 3<br/>
2 1 2 4<br/>
2 1 2 5<br/>
2 2 2 1<br/>
2 2 2 2<br/>
2 2 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
2<br/>
2<br/>
1<br/>
1<br/>
2<br/>
2<br/>
2<br/>
1<br/>
2<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Amayoneko">By Amayoneko</a></p></div>

