
# Description

<div class="content"><div class="panel_content"><span style="font-size: medium">There is a random sequence L whose element are all random numbers either -1 or 1 with the same possibility. Now we define MAVS, the abbreviate of Maximum Absolute Value Subsequence, to be any (if more than one) subsequences of L whose absolute value is maximum among all subsequences. Given the length of L, your task is to find the expectation of the absolute value of MAVS.</span></div>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">There is only one input file. The first line is the number of test cases T. T positive integers follow, each of which contains one positive number not greater than 1500 denoted the length of L.<br/>
</span></p>
<div class="panel_bottom"><span style="font-size: medium"> </span></div>
<p><span style="font-size: medium">给你一个数字L,代表数字串长。这个数字串每个元素为1或-1.</span></p>
<p><span style="font-size: medium">那么就有这个数列有2^L种可能。</span></p>
<p><span style="font-size: medium">现对每个可能的数字串，求其连续子串和，并将和取绝对值，记下最大的那个值。</span></p>
<p><span style="font-size: medium">再求出所有这些值的总和。</span></p>
<p><span style="font-size: medium">输入总和/2^L</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">For each test case, output the expectation you are required to calculate. Answers are rounded to 6 numbers after the decimal point.(as shown in the sample output)<br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
5<br/>
10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 1.000000<br/>
Case 2: 2.750000<br/>
Case 3: 4.167969<br/>
</span></div>

# Hint

<div class="content"><p></p><p>当输入2时，有</p><br/>
<p>1 1</p><br/>
<p>1 -1</p><br/>
<p>-1 1</p><br/>
<p>-1 -1</p><br/>
<p>这四种可能，其对应的值分别为(2+1+1+2)=6</p><br/>
<p>6/4=1.5</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=acm 2011 福州">acm 2011 福州</a></p></div>

