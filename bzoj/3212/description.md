
# Description

<div class="content"><p><span id="1369649389470S" style="display: none"> </span><span style="font-size: medium"><font face="Times New Roman"><br/>
You have N integers, A1, A2, ... , AN. You need to deal with two kinds of operations. One type of operation is to add some given number to each number in a given interval. The other is to ask for the sum of numbers in a given interval. <br/>
<br/>
</font></span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman"><br/>
The first line contains two numbers N and Q. 1 ≤ N,Q ≤ 100000. <br/>
The second line contains N numbers, the initial values of A1, A2, ... , AN. -1000000000 ≤ Ai ≤ 1000000000. <br/>
Each of the next Q lines represents an operation. <br/>
&#34;C a b c&#34; means adding c to each of Aa, Aa+1, ... , Ab. -10000 ≤ c ≤ 10000. <br/>
&#34;Q a b&#34; means querying the sum of Aa, Aa+1, ... , Ab. <br/>
<br/>
</font></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman"><br/>
You need to answer all Q commands in order. One answer in a line. <br/>
<br/>
</font></span></p>
<p align="left"><span id="1369649389073E" style="display: none"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 5<br/>
1 2 3 4 5 6 7 8 9 10<br/>
Q 4 4<br/>
Q 1 10<br/>
Q 2 4<br/>
C 3 6 3<br/>
Q 2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
55<br/>
9<br/>
15<br/>
</span></div>

# Hint

<div class="content"><p></p><p><font face="Times New Roman" size="3">The sums may exceed the range of 32-bit integers. </font><br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

