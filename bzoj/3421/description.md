
# Description

<div class="content"><p><span style="font-size: medium">The names of towns in Byteotia are unique sequences of exactly N  bits. There are 2^N – k towns in Byteotia, and thus, only K sequences of N  bits do not correspond to any town.<br/>
Some pairs of towns are connected with roads. Specifically, two towns are directly linked by a road if and only if their names differ in a single bit. The roads do not cross outside of towns.<br/>
Byteasar intends to take a stroll - he intends to walk from the town x  to the town y , taking the existing roads. Your task is to write a program that will determine if such a walk is possible.<br/>
</span></p>
<p><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">有</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">2^N-k</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">个点，每个点有一个独一无二的、长度为</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">n</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">的</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">01</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">串，但是有</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">k</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">个</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">01</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">串没有出现过。每两个点之间有连边当且仅当两个</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">01</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">串之间有且仅有一个位置是不同的。现在询问</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">x</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">和</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">y</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">两个字符串能不能互相到达</span></p></div>

# Input

<div class="content"><p><font size="4">In the first line of the standard input, there are two integers, N  and K (1&lt;=N&lt;=60,0&lt;=K&lt;=1000000,k&lt;=2^N-1, N*k&lt;=5000000)  separated by a single space. These are the length of town names in bits and the the number of N -bit sequences that do not correspond to any town, respectively. In the second line, there are two strings, separated by a single space, each consisting of   characters 0 and/or 1. These are the names of the towns x and y. In the K lines that follow, all the sequences of N bits that do not correspond to any town are given, one sequence per line. Each such sequence is a string of   characters 0 and/or1. You may assume that x  and  y  are not among those K sequences.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should print to the standard output the word TAK (Polish for yes) if walking from the town x to the town y  is possible, and the word NIE (Polish for no) otherwise.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
0000 1011<br/>
0110<br/>
0111<br/>
0011<br/>
1101<br/>
1010<br/>
1001<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢HJWJBSR提供译文">鸣谢HJWJBSR提供译文</a></p></div>

