
# Description

<div class="content"><div>ZCC’s English is so poor that his teacher GPS forced him to memorize words. In order to examine ZCC, GPS created a software. This software works as follow. A user inputs a string S which only consists of uppercase into this software, then the software calculates the score which string S has by using its strange methods.Initially the software stores n different words and the initial score is 1. The length of S is L. The chars of string S is labeled from 1 to L(left to right), and S[i] represent the i-th char of S. </div>
<div></div>
<div>// Prime[k] means the k-th prime number, such as Prime[1]=2, Prime[2]=3 ,Prime[8]=19.</div>
<div>Input &gt;&gt; S</div>
<div>Score = 1</div>
<div>For i = 1 to L do</div>
<div>For k=1 to n do</div>
<div>If S[j..i] equals to Word[k]</div>
<div>Score = Score * Prime[k] * ( i * 2 - j + 1 )</div>
<div>Output &lt;&lt; Score</div>
<div></div>
<div>The pseudocode above shows when input S what score we can get.</div>
<div>If n=2,L=3,Word[1]=”AB”,Word[2]=”BB” then </div>
<div>Score[ABB] = 1 * ( 2 * 2 - 1 + 1 ) * Prime[1] * ( 3 * 2 - 2 + 1 ) * Prime[2],</div>
<div>Score[CBA] = 1,</div>
<div>Score[CAB] = 1 * ( 3 * 2 - 2 + 1 ) * Prime[1];</div>
<div>ZCC has found a BUG which can help him to input strings into the software as much as he can. And the score he gets in the end is the sum of the score he gets in each input.ZCC wants to know the score he will get in the end, if he input all the different strings into the software. That is to say if the length of string is L, he can input 26^L strings in all. The answer can be very large, so what ZCC actually want is the ans Mod 5047621.</div>
<p></p></div>

# Input

<div class="content"><div>The input contains several test cases.Two integers N(1≤N≤40),L(1≤L≤10^17) will exist in the first line of each input, indicating the number of words and the length of each S you can input to the software. Next n line contains n words, the i-th line means Word[i].Let Len[i] be the length of Word[i], and Len[1]+Len[2]…+Len[n]&lt;=40.</div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output the score Mod 5047621.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
AB<br/>
BB<br/>
4 1<br/>
A<br/>
B<br/>
C<br/>
D<br/>
1 2<br/>
A<br/>
3 3<br/>
ZZ<br/>
ZZA<br/>
ZZZ</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 18894<br/>
Case #2: 56<br/>
Case #3: 899<br/>
Case #4: 20511</span></div>

# Hint

<div class="content"><p></p><div>For the second test case, all the 4 words can be got. So score is (1*2-1+1)*(2+3+5+7)+22.</div><br/>
<div>5047621=179*173*163</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

