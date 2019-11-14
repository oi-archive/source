
# Description

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">
</font></span></p><p><font face="Times New Roman"><font face="Times New Roman">To meet the ever-growing demands of his N (1 &lt;= N &lt;= 50,000) cows, <br/>
Farmer John has bought them a new soda machine. He wants to figure <br/>
out the perfect place to install the machine. <br/>
<br/>
The field in which the cows graze can be represented as a one-dimensional <br/>
number line. Cow i grazes in the range A_i..B_i (1 &lt;= A_i &lt;= B_i; <br/>
A_i &lt;= B_i &lt;= 1,000,000,000) (a range that includes its endpoints), <br/>
and FJ can place the soda machine at any integer point in the range <br/>
1..1,000,000,000. Since cows are extremely lazy and try to move <br/>
as little as possible, each cow would like to have the soda machine <br/>
installed within her grazing range. <br/>
<br/>
Sadly, it is not always possible to satisfy every cow&#39;s desires. <br/>
Thus FJ would like to know the largest number of cows that can be <br/>
satisfied. <br/>
<br/>
To demonstrate the issue, consider four cows with grazing ranges <br/>
3..5, 4..8, 1..2, and 5..10; below is a schematic of their grazing <br/>
ranges: <br/>
</font></font></p><font face="Times New Roman">
</font><font face="Times New Roman" size="3">
<pre><span style="font-size: medium"><br/>         1   2   3   4   5   6   7   8   9  10  11  12  13
<br/>         |---|---|---|---|---|---|---|---|---|---|---|---|-...
<br/>                 aaaaaaaaa
<br/>                     bbbbbbbbbbbbbbbbb
<br/>         ccccc           ddddddddddddddddddddd
<br/></span></pre>
<p></p>
</font><p></p>
<p></p>
<p></p>
<p></p>
<p align="left"><b><font color="#333399" size="5">Sample Output</font> </b></p>
<p></p><p></p>
<span id="1320118971464E" style="display: none"> </span><span style="font-size: medium"><font face="Times New Roman">
<p><br/>
As can be seen, the first, second and fourth cows share the point 5, <br/>
but the third cow&#39;s grazing range is disjoint. Thus, a maximum of <br/>
3 cows can have the soda machine within their grazing range. <br/>
有N个人要去膜拜JZ，他们不知道JZ会出现在哪里，因此每个人有一个活动范围，只要JZ出现在这个范围内就能被膜拜， <br/>
伟大的JZ当然希望膜拜他的人越多越好，但是JZ不能分身，因此只能选择一个位置出现，他最多可以被多少人膜拜呢， <br/>
这个简单的问题JZ当然交给你了 <br/>
<br/>
<br/>
</p>
</font></span><p></p>
<pre>3

OUTPUT DETAILS:

If the soda machine is placed at location 5, cows 1, 2, and 4 can be
satisfied. It is impossible to satisfy all four cows.

</pre></div>

# Input

<div class="content"><p> </p>
<p></p>
<p><span style="font-size: medium"><font face="Times New Roman">* Line 1: A single integer: N <br/>
<br/>
* Lines 2..N+1: Line i+1 contains two space-separated integers: A_i <br/>
and B_i <br/>
<br/>
</font></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">* Line 1: A single integer representing the largest number of cows <br/>
whose grazing intervals can all contain the soda machine. <br/>
</font></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 5<br/>
4 8<br/>
1 2<br/>
5 10<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
If the soda machine is placed at location 5, cows 1, 2, and 4 can be<br/>
satisfied. It is impossible to satisfy all four cows.<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

