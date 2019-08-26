
# Description

<div class="content"><div class="ptt" lang="en-US"></div>
<div class="ptx" lang="en-US">John and Brus are freshmen at the primary school. Their first home task is to learn some integer numbers. It is not so hard for the guys and they decide to impress their teacher by learning all lucky numbers between A and B, inclusive. <br/>
As you already know from the previous year contest 4 and 7 are lucky digits, and all the other digits are not lucky. A lucky number is a number that contains only lucky digits in decimal notation. <br/>
After learning all lucky numbers in [A, B] range John and Brus still have some free time and now they decide to learn additionally each lucky number N that is out of [A, B] range, but the reversed number of N is in this range. Here reversed number of N is the number N written in decimal notation, but the order of digits is reversed. For example, the reversed number of 447 is 744 and reversed number of 774474444 is 444474477. <br/>
You are given integers A and B and your task is to find the total number of lucky numbers learned by John and Brus.</div>
<div class="ptx" lang="en-US"></div>
<div class="ptx" lang="en-US">
<div><span>    </span>只有4和7组成的数字被定义成lucky-number（一下简称LN）。求出[a,b]区间内的LN数量和本身不在[a,b]区间内但是逆序之后在[a,b]区间内的LN数量。其中ab的长度小于等于48。</div>
</div></div>

# Input

<div class="content"><div class="ptx" lang="en-US">The first line contains single integer T – the number of test cases. Each test case consists of a single line containing two integers A and B separated by a single space.</div></div>

# Output

<div class="content"><p class="pst"> For each test case print a single line containing the total number of lucky numbers learned by John and Brus.</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
1 100 <br/>
44 47<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
3<br/>
Hint<br/>
<br/>
Constraints: <br/>
1 ≤ T ≤ 74, <br/>
1 ≤ A ≤ B ≤ 100000000000000000000000000000000000000000000000 (1047).</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Seerc2009">Seerc2009</a></p></div>

