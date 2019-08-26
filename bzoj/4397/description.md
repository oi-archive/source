
# Description

<div class="content"><p>Farmer John&#39;s N cows, conveniently numbered 1…N, are all standing in a row (they seem to do so often that it now takes very little prompting from Farmer John to line them up). Each cow has a breed ID: 1 for Holsteins, 2 for Guernseys, and 3 for Jerseys. Farmer John would like your help counting the number of cows of each breed that lie within certain intervals of the ordering.</p>
<p></p>
<p>给定一个长度为N的序列，每个位置上的数只可能是1，2，3中的一种。</p>
<p>有Q次询问，每次给定两个数a,b，请分别输出区间[a,b]里数字1，2，3的个数。</p>
<p></p></div>

# Input

<div class="content"><p>The first line of input contains NN and QQ (1≤N≤100,000 1≤Q≤100,000).<br/>
The next NN lines contain an integer that is either 1, 2, or 3, giving the breed ID of a single cow in the ordering.<br/>
The next QQ lines describe a query in the form of two integers a,b (a≤b).</p></div>

# Output

<div class="content"><p>For  each of the QQ queries (a,b), print a line containing three numbers:  the number of cows numbered a…b that are Holsteins (breed 1), Guernseys  (breed 2), and Jerseys (breed 3).</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
2<br/>
1<br/>
1<br/>
3<br/>
2<br/>
1<br/>
1 6<br/>
3 3<br/>
2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 2 1<br/>
1 0 0<br/>
2 0 1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver鸣谢Claris提供译文">Silver鸣谢Claris提供译文</a></p></div>

