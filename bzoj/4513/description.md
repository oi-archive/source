
# Description

<div class="content"><p>有一个 n 行 m 列的表格，行从 0 到 n−1 编号，列从 0 到 m−1 编号。每个格子都储存着能量。最初，第 i 行第 j 列的格子储存着 (i xor j) 点能量。所以，整个表格储存的总能量是，</p>
<div><img src="/source/bzoj/4513/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8xKDIpLnBuZw==.png" width="181" height="91" alt=""/></div>
<div>随着时间的推移，格子中的能量会渐渐减少。一个时间单位，每个格子中的能量都会减少 1。显然，一个格子的能量减少到 0 之后就不会再减少了。</div>
<div>也就是说，k 个时间单位后，整个表格储存的总能量是，</div>
<div><img src="/source/bzoj/4513/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8yKDIpLnBuZw==.png" width="320" height="98" alt=""/></div>
<div>给出一个表格，求 k 个时间单位后它储存的总能量。</div>
<div>由于总能量可能较大，输出时对 p 取模。</div>
<p></p></div>

# Input

<div class="content"><p>第一行一个整数 T，表示数据组数。接下来 T 行，每行四个整数 n、m、k、p。</p>
<div></div></div>

# Output

<div class="content"><p> 共 T 行，每行一个数，表示总能量对 p 取模后的结果</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 2 0 100<br/>
3 3 0 100<br/>
3 3 1 100</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
12<br/>
6</span></div>

# Hint

<div class="content"><p></p><p> T=5000，n≤10^18，m≤10^18，k≤10^18，p≤10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Menci上传">鸣谢Menci上传</a></p></div>

