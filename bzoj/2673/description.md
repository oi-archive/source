
# Description

<div class="content"><p>有一个芯片，芯片上有N*N（1≤N≤40）个插槽，可以在里面装零件。</p>
<p>有些插槽不能装零件，有些插槽必须装零件，剩下的插槽随意。</p>
<p>要求装好之后满足如下两条要求：</p>
<p>1、第 i 行和第 i 列的零件数目必须一样多（1≤i≤N）。</p>
<p>2、第 i 行的零件数目不能超过总的零件数目的 A/B（1≤i≤N，0≤A≤B≤1000，B≠0）。</p>
<p>求最多可以另外放多少个零件（就是除掉必须放的）。如果无解输出impossible。</p></div>

# Input

<div class="content"><p>The input consists of several test cases. Each case starts with a line containing three integers: The size of the chip N (1&lt;=N&lt;=40), and A and B (1&lt;=A&lt;=1000, 0&lt;=A&lt;=B) as described above. Each of the following N lines contains N characters describing the slots, one of `.&#39;, `/&#39; or `C&#39;, as described above.</p>
<p>The last test case is followed by a line containing three zeros.</p>
<p></p></div>

# Output

<div class="content"><p>For each test case, display a single line beginning with the case number. If there is a solution, display the maximum number of widgets that can be added to the chip. Display ``impossible&#34; if there is no solution.</p>
<p>Follow the format of the sample output.</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 1<br/>
/.<br/>
//<br/>
2 50 100<br/>
/.<br/>
C/<br/>
2 100 100<br/>
./<br/>
C.<br/>
5 3 10<br/>
CC/..<br/>
././/<br/>
..C.C<br/>
/.C..<br/>
/./C/<br/>
5 2 10<br/>
CC/..<br/>
././/<br/>
..C.C<br/>
/.C..<br/>
/./C/<br/>
0 0 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 0<br/>
Case 2: 1         <br/>
Case 3: impossible<br/>
Case 4: 7         <br/>
Case 5: impossible<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

