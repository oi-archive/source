
# Description

<div class="content"><p></p>
<p><span style="font-size: medium"> Farmer John&#39;s N cows (1 &lt;= N &lt;= 100,000) are lined up in a row. Each cow is identified by an integer &#34;breed ID&#34; in the range 0...1,000,000,000; the breed ID of the ith cow in the lineup is B(i). Multiple cows can share the same breed ID. FJ thinks that his line of cows will look much more impressive if there is a large contiguous block of cows that all have the same breed ID. In order to create such a block, FJ chooses up to K breed IDs and removes from his lineup all the cows having those IDs. Please help FJ figure out the length of the largest consecutive block of cows with the same breed ID that he can create by doing this. </span></p>
<p></p>
<div style="text-indent: 15.05pt"><b><span style="font-size: 15pt">给你一个长度为</span></b><b><span style="font-size: 15pt">n(1&lt;=n&lt;=100,000)</span></b><b><span style="font-size: 15pt">的自然数数列，其中每一个数都小于等于</span></b><b><span style="font-size: 15pt">10</span></b><b><span style="font-size: 15pt">亿，现在给你一个</span></b><b><span style="font-size: 15pt">k</span></b><b><span style="font-size: 15pt">，表示你最多可以删去</span></b><b><span style="font-size: 15pt">k</span></b><b><span style="font-size: 15pt">类数。数列中相同的数字被称为一类数。设该数列中满足所有的数字相等的连续子序列被叫做完美序列，你的任务就是通过删数使得该数列中的最长完美序列尽量长。</span></b></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: N and K. <br/>
* Lines 2..1+N: Line i+1 contains the breed ID B(i). <br/>
<br/>
</span></p></div>

# Output

<div class="content"><p><br/>
* Line 1: The largest size of a contiguous block of cows with identical breed IDs that FJ can create.</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 1 <br/>
2 <br/>
7 <br/>
3 <br/>
7 <br/>
7 <br/>
3 <br/>
7 <br/>
5 <br/>
7 <br/>
<br/>
INPUT DETAILS: There are 9 cows in the lineup, with breed IDs 2, 7, 3, 7, 7, 3, 7, 5, 7. FJ would like to remove up to 1 breed ID from this lineup. <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
<br/>
OUTPUT DETAILS: By removing all cows with breed ID 3, the lineup reduces to 2, 7, 7, 7, 7, 5, 7. In this new lineup, there is a contiguous block of 4 cows with the same breed ID (7). <br/>
</span></div>

# Hint

<div class="content"><p></p><div><b><span style="font-size: 15pt">样例解释：</span></b></div><br/>
<div><b><span style="font-size: 15pt">  </span></b><b><span style="font-size: 15pt">长度为</span></b><b><span style="font-size: 15pt">9</span></b><b><span style="font-size: 15pt">的数列，最多只能删去</span></b><b><span style="font-size: 15pt">1</span></b><b><span style="font-size: 15pt">类数。</span></b></div><br/>
<div><b><span style="font-size: 15pt">  </span></b><b><span style="font-size: 15pt">不删，最长完美序列长度为</span></b><b><span style="font-size: 15pt">2.</span></b></div><br/>
<div><b><span style="font-size: 15pt">  </span></b><b><span style="font-size: 15pt">删去一类数</span></b><b><span style="font-size: 15pt">3</span></b><b><span style="font-size: 15pt">，序列变成</span></b><b><span style="font-size: 15pt">2 7 7 7 7 5 7</span></b><b><span style="font-size: 15pt">，最长完美序列长度为</span></b><b><span style="font-size: 15pt">4.</span></b><b><span style="font-size: 15pt">因此答案为</span></b><b><span style="font-size: 15pt">4.</span></b></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

