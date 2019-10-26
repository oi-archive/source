
# Description

<div class="content"><div>
<div>对于一个01串s，定义函数f(s)为s每一位的异或和，例如f(111)=1,f(110)=0,f(101)=0,f(100)=1。</div>
<div>一个01串s是好串，当且仅当其满足以下条件：</div>
<div>串的长度为2的幂次方。</div>
<div>存在两个非负整数x,b，使得i∈[0,|s|-1],si=f(i and x)xorb</div>
<div>（下标从0开始，此处f函数计算的是i and x对应的二进制串的值）。</div>
<div>现对于一个01串，可以使用区间取反操作，即选定一个区间[l,r],0≤l≤r&lt;|s|，</div>
<div>并将[l,r]中的每一位取反（即1→0,0→1）。</div>
<div>现在给出一个长度为n的01串s，q次询问子串sl,r最少经过多少次区间取反操作变成好串</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数n。</div>
<div>第二行包含一个长为n的01串s。</div>
<div>第三行包含一个整数q。</div>
<div>接下来q行每行两个整数表示l,r。保证子串的长度为2的幂次方，且下标从0开始。</div>
<div>n,q≤5000</div>
<p></p></div>

# Output

<div class="content"><div>输出q行，对于每个询问输出对应的答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
00000101<br/>
3<br/>
0 7<br/>
2 5<br/>
0 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 <br/>
1 <br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

