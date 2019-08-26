
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">Inspector Byteasar is investigating a crime that took place on the premises of a software development company. He is trying to establish the chain of events. Unfortunately, the programmers are rather scatterbrained. Statements of the kind &#34;Well, when I checked at 14:42, there were five other programmers logged in on the server.&#34; are the most informative of those that Byteasar could get.</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">It is known that every programmer came to office at some point during that day, spent some time in there without going out, and then left for good, never coming back on the same day.</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">Byteasar, confused by the programmers&#39; statements, is not sure if he should rely on them. In fact, he is wondering whether it is at all possible that they all tell the truth. He asks you for help in finding that out.</span></span></div>
<div style="background: white" align="left"><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">一天公司有</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">n</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">个员工和</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">m</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">个员工记录，每个员工只会在连续的一段时间内工作。当然写观察记录的时候肯定会在工作。记录会给出当时除了他还有多少人在公司。现在给出</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">m</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">条记录分别是谁写的、什么时候写的以及写的时候还有多少人。求第</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">k</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">条记录使得前</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">k</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">条记录可以同时存在不矛盾，且前</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">k+1</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">条记录是矛盾的。输出这个</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">k</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">。</span></div></div>

# Input

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">In the first line of the standard input, there is an integer Z (1&lt;=Z&lt;=50) , the number of data sets. The lines that follow contain the Z data sets.</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">The first line of each data set holds two integers, N  and M , separated by a single space(1&lt;=N,M&lt;=100000) . These are the number of programmers working in the office and the number of statements recorded by Byteasar. The programmers are numbered from 1 to N.</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">Each of the m lines that follow describes a single statement. Each such line contains three integers  ,  , and  , separated by single spaces 1&lt;=T&lt;=M,1&lt;=j&lt;=N 0&lt;=i&lt;=N</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">These indicate that the programmer no.   confessed that at time   he was in the office and there were   more programmers apart from him. We assume that the programmers came in to the office and left it at times different from those appearing in the statements, i.e., either before, after or in between them.</span></span></div></div>

# Output

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #444444">For each data set, your program should print a single positive integer to the standard output. Printing out the number K(1&lt;=K&lt;=M) indicates that the first   statements given on the input can be true but the first K+1  statements cannot. In particular, if K=M, then all the statements given as input can be true.</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 5<br/>
1 1 1<br/>
1 2 1<br/>
2 3 1<br/>
4 1 1<br/>
4 2 1<br/>
3 3<br/>
3 3 0<br/>
2 2 0<br/>
1 1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
3<br/>
Explanation of the example: In the first data set, the statements given by programmers cannot all be true. The programmers 1 and 2 stated that they were in the office between times 1 and 4 but the programmer 3 stated that at time 2 there was only a single person apart from him there. If we discount that last statement, the remaining ones can be true.<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢HJWJBSR提供译文">鸣谢HJWJBSR提供译文</a></p></div>

