
# Description

<div class="content"><img border="0" src="/source/bzoj/1988/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5ODguanBn.jpg"/> 
</div>

# Input

<div class="content">输入只有1行，4个整数，分别为 a,m,b,n。

</div>

# Output

<div class="content">从最高项到最低项输出多项式F的系数
ad, ad-1,…a1,a0
</div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
3 2 2 3<br/>
<br/>
<br/>
样例输出2：<br/>
2 2 3 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1：<br/>
1 0 -9 -4 27 -36 -23<br/>
<br/>
样例输出2：<br/>
1 0 -8 0 18 0 -104 0 1<br/>
<br/>
数据范围：<br/>
	t&lt;=4<br/>
	m*n&lt;=20<br/>
	保证答案F的系数范围在[-2^31+1，2^31-1]以内<br/>
</span></div>

# Hint

<div class="content"><p>可以证明答案F的最高次数为n*m。<br/>
注意输出的格式，一切形如+2，+0，-0的输出均视为不合法输出。<br/>
<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Acm Japan 2007">Acm Japan 2007</a></p></div>

