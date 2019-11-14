
# Description

<div class="content"><div>定义二元运算 opt 满足</div>
<div><img src="/source/bzoj/4836/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNC8xMTEuSlBH.JPG" width="306" height="83" alt=""/></div>
<div></div>
<div>现在给定一个长为 n 的数列 a 和一个长为 m 的数列 b ，接下来有 q 次询问。每次询问给定一个数字 c </div>
<div>你需要求出有多少对 (i, j) 使得 a_i  opt b_j=c 。</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行是一个整数 T (1≤T≤10) ，表示测试数据的组数。</div>
<div>对于每组测试数据：</div>
<div>第一行是三个整数 n,m,q (1≤n,m,q≤50000) 。</div>
<div>第二行是 n 个整数，表示 a_1,a_2,?,a_n (0≤a_1,a_2,?,a_n≤50000) 。</div>
<div>第三行是 m 个整数，表示 b_1,b_2,?,b_m (0≤b_1,b_2,?,b_m≤50000) 。</div>
<div>第四行是 q 个整数，第 i 个整数 c_i (0≤c_i≤100000) 表示第 i 次查询的数。</div>
<div></div>
<div></div></div>

# Output

<div class="content"><p>对于每次查询，输出一行，包含一个整数，表示满足条件的 (i, j) 对的个数。</p>
<div></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 1 5<br/>
1 3<br/>
2<br/>
1 2 3 4 5<br/>
2 2 5<br/>
1 3<br/>
2 4<br/>
1 2 3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
1<br/>
0<br/>
0<br/>
1<br/>
0<br/>
1<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

