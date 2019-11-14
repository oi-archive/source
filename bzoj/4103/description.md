
# Description

<div class="content"><p>给定长度为n的数列X={x1,x2,...,xn}和长度为m的数列Y={y1,y2,...,ym}，令矩阵A中第i行第j列的值Aij=xi xor  yj，每次询问给定矩形区域i∈[u,d],j∈[l,r]，找出第k大的Aij。</p>
<div></div></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m，分别表示两个数列的长度</p>
<div>第二行包含n个非负整数xi</div>
<div>第三行包含m个非负整数yj</div>
<div>第四行包含一个正整数p，表示询问次数</div>
<div>随后p行，每行均包含5个正整数，用来描述一次询问，每行包含五个正整数u,d,l,r,k，含义如题意所述。</div>
<div></div></div>

# Output

<div class="content"><p>共p行，每行包含一个非负整数，表示此次询问的答案。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 4<br/>
7 6 5<br/>
3<br/>
1 2 1 2 2<br/>
1 2 1 3 4<br/>
2 3 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
5<br/>
1</span></div>

# Hint

<div class="content"><p></p><p> 对于100%的数据，0&lt;=Xi,Yj&lt;2^31,</p><br/>
<div></div><br/>
<div>1&lt;=u&lt;=d&lt;=n&lt;=1000,</div><br/>
<div></div><br/>
<div>1&lt;=l&lt;=r&lt;=m&lt;=300000,</div><br/>
<div></div><br/>
<div>1&lt;=k&lt;=(d-u+1)*(r-l+1),</div><br/>
<div></div><br/>
<div>1&lt;=p&lt;=500</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

