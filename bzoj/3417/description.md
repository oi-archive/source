
# Description

<div class="content"><p><span style="font-size: medium; ">Young Bytensson loves to hang out in the port tavern, where he often listens to the sea dogs telling their tales of seafaring. Initially, he believed them all, however incredible they sounded. Over time though, he became suspicious. He has decided to write a program that will verify if there may be any grain of truth in those tall stories. Bytensson reasoned that while he cannot tell if the sailors indeed weathered all those storms, he can at least find out if their travel itineraries make sense. This is a task for a programmer, which Bytensson, unfortunately, is not. Help him out!<br/>
There are   ports and   waterways connecting them in the waters frequented by the sailors Bytensson listened to. If there is a waterway between two ports, then sailing from one to the other is possible. Any waterway can be sailed in both directions.<br/>
Bytensson got to know K seafaring tales. Each tells of a sailor who began his journey in one port, sailed a number of waterways, and ended up in another port, which may have been the one he initially set sail from. The sailor in question may have sailed through the same waterway many times, each time in any direction.<br/>
</span></p>
<p><span style="font-size: medium; "><br type="_moz"/>
</span></p>
<p><span style="font-size: medium; ">一个<span lang="EN-US">n</span>点<span lang="EN-US">m</span>边无向图，边权均为<span lang="EN-US">1</span>，有<span lang="EN-US">k</span>个询问</span></p>
<p class="MsoPlainText"><span style="font-size: medium; ">每次询问给出<span lang="EN-US">(s,t,d)</span>，要求回答是否存在一条从<span lang="EN-US">s</span>到<span lang="EN-US">t</span>的路径，长度为<span lang="EN-US">d</span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoPlainText"><span style="font-size: medium; ">路径不必是简单路<span lang="EN-US">(</span>可以自交<span lang="EN-US">)</span></span><span lang="EN-US"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p><font size="4">In the first line of the standard input, there are three integers, N,M and K (2&lt;=N&lt;=5000,1&lt;=M&lt;=5000,1&lt;=K&lt;=1000000) These denote, respectively: the number of ports in the waters frequented by the sailors who told Bytensson their stories, the number of waterways, and the number of tales.<br/>
The M lines that follow specify the waterways. A single waterway&#39;s description consists of a single line that contains two integers, a and b (1&lt;=a,b&lt;=N,a&lt;&gt;b) separated by a single space; these specify the numbers of ports at the two ends of this particular waterway.<br/>
The K lines that follow specify the tales that Bytensson has heard. A single tale&#39;s description consists of a single line with three integers, s,t  and d (1&lt;=S,T&lt;=N,1&lt;=d&lt;=1000000000) separated by single spaces. These indicate that the tale&#39;s protagonist set sail from port no. s, ended the journey in port no. t, and sailed exactly d times through various waterways.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should print exactly K lines to the standard output; the i-th of them should contain the word TAK (Polish for yes) if the journey described in the i-th tale (in input order) could have taken place. If it could not, then the line should contain the word NIE(Polish for no).<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 7 4<br/>
1 2<br/>
2 3<br/>
3 4<br/>
5 6<br/>
6 7<br/>
7 8<br/>
8 5<br/>
2 3 1<br/>
1 4 1<br/>
5 5 8<br/>
1 8 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE<br/>
TAK<br/>
NIE<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="138" width="420" alt="" src="/source/bzoj/3417/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS9hZmYoNCkuanBn.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Wcmg提供译文">鸣谢Wcmg提供译文</a></p></div>

