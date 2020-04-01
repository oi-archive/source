
# Description

<div class="content"><p><span style="font-size: medium">给定n个非负整数A[1], A[2], ……, A[n]。<br/>
对于每对(i, j)满足1 &lt;= i &lt; j &lt;= n，得到一个新的数A[i] xor A[j]，这样共有n*(n-1)/2个新的数。求这些数（不包含A[i]）中前k小的数。<br/>
注：xor对应于pascal中的“xor”，C++中的“^”。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行2个正整数 n,k，如题所述。<br/>
以下n行，每行一个非负整数表示A[i]。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4"> 共一行k个数，表示前k小的数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1<br/>
1<br/>
3<br/>
4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 2 2 5 5<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【样例解释】<br/><br/>
1 xor 1 = 0 (A[1] xor A[2])<br/><br/>
1 xor 3 = 2 (A[1] xor A[3])<br/><br/>
1 xor 4 = 5 (A[1] xor A[4])<br/><br/>
1 xor 3 = 2 (A[2] xor A[3])<br/><br/>
1 xor 4 = 5 (A[2] xor A[4])<br/><br/>
3 xor 4 = 7 (A[3] xor A[4])<br/><br/>
前5小的数：0 2 2 5 5<br/><br/>
【数据范围】<br/><br/>
 对于100%的数据，2 &lt;= n &lt;= 100000； 1 &lt;= k &lt;= min{250000, n*(n-1)/2}；<br/><br/>
        0 &lt;= A[i] &lt; 2^31<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

