
# Description

<div class="content"><p><span style="font-size: medium"> The cows keep getting in trouble by taking rides on Farmer John&#39;s tractor, so he has hidden the keys to the tractor in a fancy new safe in his office. Undeterred, the cows have vowed to try and break into this safe. The safe is protected by a rather complicated passcode system. The passcode entry system is arranged as a rooted tree of N (1 &lt;= N &lt;= 20,000) nodes, each of which requires a digit between 0 and 9. The nodes are indexed 0..N-1. The only information that the cows have is that certain sequences of length 5 do not occur along particular paths upwards through the tree. For instance, suppose the tree is the following (rooted at A): </span></p>
<p><span style="font-size: medium"><img height="106" width="208" alt="" src="source/bzoj/3537/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC8xLmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium"> The cows might know that the sequence 01234 does not occur starting at F, and that the sequence 91234 does not occur starting at E. This information rules out 19 possible passcodes: all those of the form </span></p>
<p><span style="font-size: medium"><img height="106" width="208" alt="" src="source/bzoj/3537/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC8yLmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium">or</span></p>
<p><span style="font-size: medium"> <img height="106" width="208" alt="" src="source/bzoj/3537/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC8zLmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium"> which gives 19 once we account for the fact that </span></p>
<p><span style="font-size: medium"><img height="106" width="208" alt="" src="source/bzoj/3537/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC80LmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium">appears twice. Given M (1 &lt;= M &lt;= 50,000) length-5 sequences, together with their starting nodes in the tree, help the cows figure out how many passcodes have been ruled out. You should compute your answer modulo 1234567. </span></p>
<p></p>
<p></p>
<p></p>
<p></p>
<div><span style="font-size: medium"><span style="background: white; color: black">有一棵N</span><span style="background: white; color: black">个节点的有根树</span><span style="background: white; color: black">,</span><span style="background: white; color: black">每个节点可以填0~9.</span></span></div>
<div><span style="font-size: medium"><span style="background: white; color: black">有M</span><span style="background: white; color: black">个事实</span><span style="background: white; color: black">,</span><span style="background: white; color: black">就是从</span><span style="background: white; color: black">X</span><span style="background: white; color: black">开始往祖先一直跑的的包含</span><span style="background: white; color: black">X</span><span style="background: white; color: black">的</span><span style="background: white; color: black">5</span><span style="background: white; color: black">个节点</span><span style="background: white; color: black">(</span><span style="background: white; color: black">保证</span><span style="background: white; color: black">X</span><span style="background: white; color: black">上面一定存在这样一条路径</span><span style="background: white; color: black">,</span><span style="background: white; color: black">也就是说</span><span style="background: white; color: black">X</span><span style="background: white; color: black">的深度至少为</span><span style="background: white; color: black">5),</span><span style="background: white; color: black">一定不是ABCDE.(0&lt;=A,B,C,D,E&lt;=9)</span></span></div>
<div><span style="font-size: medium"><span style="background: white; color: black">求,</span><span style="background: white; color: black">根据这</span><span style="background: white; color: black">M</span><span style="background: white; color: black">个事实</span><span style="background: white; color: black">,</span><span style="background: white; color: black">共有多少种给这棵树全部填上数的方案一定是不可能的.</span></span></div>
<p></p></div>

# Input

<div class="content"><p><font size="4">* Line 1: Two space-separated integers, N and M.</font></p>
<p><font size="4"> * Lines 2..N: Line i+1 contains a single integer p(i), denoting the parent of node i in the tree (0 &lt;= p(i) &lt; i). </font></p>
<p><font size="4">* Lines N+1..N+M: Line N+i describes the ith sequence known not to occur in the code. The line will contain v(i) and s(i) separated by a space, where v(i) is the starting node of the sequence, and s(i) is a 5-digit string known not to occur starting at v(i) and proceeding upward in the tree. It is guaranteed that the root is at least 4 steps upward from v(i).</font></p></div>

# Output

<div class="content"><p><font size="4">* Line 1: A single integer giving the number of ruled-out configurations, modulo 1234567. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 2<br/>
0<br/>
1<br/>
2<br/>
3<br/>
3<br/>
4 01234<br/>
5 91234<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">19 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold By liyizhen2">Gold By liyizhen2</a></p></div>

