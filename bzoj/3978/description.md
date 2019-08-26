
# Description

<div class="content"><div>斐波那契01字符串的定义如下</div>
<div>F(n) =</div>
<div>{</div>
<div>0<span class="Apple-tab-span" style="white-space:pre">	</span> if n = 0</div>
<div>1<span class="Apple-tab-span" style="white-space:pre">	</span> if n = 1</div>
<div>F(n-1)+F(n-2)<span class="Apple-tab-span" style="white-space:pre">	</span>if n &gt;= 2</div>
<div>}</div>
<div>这里+的定义是字符串的连接。F(n)的前几个元素如下：</div>
<div>F(0)=0</div>
<div>F(1)=1</div>
<div>F(2)=10</div>
<div>F(3)=101</div>
<div>F(4)=10110</div>
<div>F(5)=10110101</div>
<div>F(6)=1011010110110</div>
<div>F(7)=101101011011010110101</div>
<div>F(8)=1011010110110101101011011010110110</div>
<div>F(9)=1011010110110101101011011010110110101101011011010110101</div>
<div>给定一个模式串p和一个数n，p在F(n)中出现了多少次？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>每个测试点包含多组测试数据。</div>
<div>
<div>每组测试数据的第一行包含一个正整数n。第二行包含模式串p。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每个测试数据，输出测试数据编号和p在F(n)出现的次数。出现的位置可能会重叠。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
10<br/>
7<br/>
10<br/>
6<br/>
01<br/>
6<br/>
101<br/>
96<br/>
10110101101101<br/>
样例输出<br/>
Case 1: 5<br/>
Case 2: 8<br/>
Case 3: 4<br/>
Case 4: 4<br/>
Case 5: 7540113804746346428<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><div>数据规模和约定</div><br/>
<div>0&lt;=n&lt;=100</div><br/>
<div>p非空且包含最多100000个字符</div><br/>
<div>p出现的次数严格小于2^63。</div><br/>
<div>关于多组测试数据</div><br/>
<div>Case Limit &lt;= 30</div><br/>
<div>存在20组数据满足n&lt;=20,len(p)&lt;=100</div><br/>
<div>另有20%的数据满足len(p)&lt;=100（总共有百分之多少呢？）</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

