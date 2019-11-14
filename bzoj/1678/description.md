
# Description

<div class="content"><p><span style="font-size: medium">Bessie&#39;s been appointed the new watch-cow for the farm. Every night, it&#39;s her job to walk across the farm and make sure that no evildoers are doing any evil. She begins at the barn, makes her patrol, and then returns to the barn when she&#39;s done. If she were a more observant cow, she might be able to just walk each of M (1 &lt;= M &lt;= 50,000) bidirectional trails numbered 1..M between N (2 &lt;= N &lt;= 10,000) fields numbered 1..N on the farm once and be confident that she&#39;s seen everything she needs to see. But since she isn&#39;t, she wants to make sure she walks down each trail exactly twice. It&#39;s also important that her two trips along each trail be in opposite directions, so that she doesn&#39;t miss the same thing twice. A pair of fields might be connected by more than one trail. Find a path that Bessie can follow which will meet her requirements. Such a path is guaranteed to exist.</span></p>
<div><span style="font-size: medium">约翰有N(2≤N≤10000)个农场，它们由M(1≤M≤50000)条双向路连接．</span><span style="font-size: medium">贝茜从农场1出发去巡逻．每条路必须由两个方向各走一遍，最后回到农场1．题目保证这样的路径存在．</span><span style="font-size: medium">请输出这样的路径．</span></div></div>

# Input

<div class="content"><p>* Line 1: Two integers, N and M.</p>
<p>* Lines 2..M+1: Two integers denoting a pair of fields connected by a path.</p>
<p></p>
<div><span style="font-size: medium">    第1行输入N，M;</span></div>
<div><span style="font-size: medium">   之后M行输入一条路的两个端点．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Lines 1..2M+1: A list of fields she passes through, one per line, beginning and ending with the barn at field 1. If more than one solution is possible, output any solution. </span></p>
<div><span style="font-size: medium">    输出经过的农场，一行一个．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5//四个点,五条边<br/>
1 2<br/>
1 4<br/>
2 3<br/>
2 4<br/>
3 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
4<br/>
2<br/>
1<br/>
4<br/>
3<br/>
2<br/>
4<br/>
1<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie starts at 1 (barn), goes to 2, then 3, etc...<br/>
</span></div>

# Hint

<div class="content"><p></p><p>请不要提交....</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

