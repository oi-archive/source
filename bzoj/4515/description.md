
# Description

<div class="content"><div>Alice 和 Bob 在玩一个游戏。</div>
<div>游戏在一棵有 n 个点的树上进行。最初，每个点上都只有一个数字，那个数字是 123456789123456789。</div>
<div>有时，Alice 会选择一条从 s 到 t 的路径，在这条路径上的每一个点上都添加一个数字。对于路径上的一个点 r，</div>
<div>若 r 与 s 的距离是 dis，那么 Alice 在点 r 上添加的数字是 a×dis+b。有时，Bob 会选择一条从 s 到 t 的路径。</div>
<div>他需要先从这条路径上选择一个点，再从那个点上选择一个数字。</div>
<div>Bob 选择的数字越小越好，但大量的数字让 Bob 眼花缭乱。Bob 需要你帮他找出他能够选择的最小的数字。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个数字 n、m，表示树的点数和进行的操作数。</div>
<div>接下来 n−1 行，每行三个数字 u、v、w，表示树上有一条连接 u、v 的边，长度是 w。</div>
<div>接下来 m 行。每行第一个数字是 1 或 2。</div>
<div>若第一个数是 1，表示 Alice 进行操作，接下来四个数字 s、t、a、b。</div>
<div>若第一个数是 2，表示 Bob 进行操作，接下来四个数字 s、t。</div>
<div></div></div>

# Output

<div class="content"><p>每当 Bob 进行操作，输出一行一个数，表示他能够选择的最小的数字</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2 10<br/>
2 3 20<br/>
2 1 3<br/>
1 2 3 5 6<br/>
2 2 3<br/>
1 2 3 -5 -6<br/>
2 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">123456789123456789<br/>
6<br/>
-106</span></div>

# Hint

<div class="content"><p></p><p> n≤100000，m≤100000，∣a∣≤10000,<span style="line-height: 1.7;">0&lt;=w，|b|&lt;=10^9</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Menci上传">鸣谢Menci上传</a></p></div>

