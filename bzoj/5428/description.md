
# Description

<div class="content"><div>对于一个序列A，S1为A一阶求和序列，即S1n=∑Ai(1&lt;=i&lt;=n) ，S1的一阶求和序列S2则为A的二阶求和序列……以此类推SK为A的K阶求和序列。现在要实现以下两个操作：</div>
<div>C L R D：在A序列的[L,R]位置所有数同时加上D。</div>
<div>Q L R：询问SK序列的[L,R]位置所有数的和对10^9+7取模的结果。</div>
<p></p></div>

# Input

<div class="content"><div>第一行是三个正整数N，M，K。其中N表示序列的长度、M表示操作次数、K表示询问的序列是SK。</div>
<div>接下来M行，每行代表一个操作，格式如题目描述。</div>
<div>初始A序列中所有数都为0，序列从1开始标号：A1，A2，A3 ......。</div>
<div>N&lt;=200000,M&lt;=200000,k&lt;=10</div>
<p></p></div>

# Output

<div class="content"><div>对于每一个询问输出一行一个整数表示答案对10^9+7取模的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 1<br/>
Q 1 5<br/>
C 2 3 1<br/>
Q 1 5<br/>
C 4 5 2<br/>
Q 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
7<br/>
13<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

