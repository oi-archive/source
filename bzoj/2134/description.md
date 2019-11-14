
# Description

<div class="content"><p><img alt="" border="0" src="/source/bzoj/2134/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxMzQuanBn.jpg"/></p></div>

# Input

<div class="content"><div>n很大，为了避免读入耗时太多，</div>
<div>输入文件只有5个整数参数n, A, B, C, a1，</div>
<div>由上交的程序产生数列a。</div>
<div>下面给出pascal/C/C++的读入语句和产生序列的语句（默认从标准输入读入）： </div>
<div>// for pascal </div>
<div>readln(n,A,B,C,q[1]); </div>
<div>for i:=2 to n do q[i] := (int64(q[i-1]) * A + B) mod 100000001; </div>
<div>for i:=1 to n do q[i] := q[i] mod C + 1; </div>
<div></div>
<div>// for C/C++ </div>
<div>scanf(&#34;%d%d%d%d%d&#34;,&amp;n,&amp;A,&amp;B,&amp;C,a+1); </div>
<div>for (int i=2;i&lt;=n;i++) a[i] = ((long long)a[i-1] * A + B) % 100000001; </div>
<div>for (int i=1;i&lt;=n;i++) a[i] = a[i] % C + 1; </div>
<div>选手可以通过以上的程序语句得到n和数列a（a的元素类型是32位整数），</div>
<div>n和a的含义见题目描述。</div>
<div> 2≤n≤10000000, 0≤A,B,C,a1≤100000000</div></div>

# Output

<div class="content"><p>输出一个实数，表示gx期望做对的题目个数，保留三位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 0 4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.167<br/>
【样例说明】<br/>
a[] = {2,3,1}<br/>
正确答案	gx的答案	做对题目	出现概率<br/>
{1,1,1}	{1,1,1}	3	1/6<br/>
{1,2,1}	{1,1,2}	1	1/6<br/>
{1,3,1}	{1,1,3}	1	1/6<br/>
{2,1,1}	{1,2,1}	1	1/6<br/>
{2,2,1}	{1,2,2}	1	1/6<br/>
{2,3,1}	{1,2,3}	0	1/6<br/>
共有6种情况，每种情况出现的概率是1/6，gx期望做对(3+1+1+1+1+0)/6 = 7/6题。（相比之下，lc随机就能期望做对11/6题）</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

