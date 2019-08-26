
# Description

<div class="content"><p><span style="font-size: medium"><br/>
dnc1994要用&#34;&lt;&#34;和&#34;=&#34;两种符号连接变量，一个合法的方案必须满足：<br/>
1) 大小关系符合逻辑；<br/>
2) 形如 A = B &lt; C 与 B = A &lt; C 的两个方案被认为相同。<br/>
现在dnc1994请你求出连接N个变量的方案数。</span></p>
<p><span style="font-size: medium">比如连接 A、B、C 3个变量，有如下13种方案：<br/>
1)  A = B = C<br/>
2)  A = B &lt; C<br/>
3)  A &lt; B = C<br/>
4)  A &lt; B &lt; C<br/>
5)  A &lt; C &lt; B<br/>
6)  A = C &lt; B<br/>
7)  B &lt; A = C<br/>
8)  B &lt; A &lt; C<br/>
9)  B &lt; C &lt; A<br/>
10) B = C &lt; A<br/>
11) C &lt; A = B<br/>
12) C &lt; A &lt; B<br/>
13) C &lt; B &lt; A</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行一个正整数TEST(1 &lt;= TEST &lt;= 1000)，表示数据组数。<br/>
接下来TEST行，每行一个正整数(1 &lt;= N &lt;= 50)，表示变量的个数。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出TEST行，每行一个整数表示方案数。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1<br/>
3<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
13<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

