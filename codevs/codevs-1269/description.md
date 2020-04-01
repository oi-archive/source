<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Welcome to the Hungary Games! The streets of Budapest form a twisted network of one-way streets.</p>
<p>欢迎来到匈牙利游戏！布达佩斯（匈牙利首都）的街道形成了一个弯曲的单向网络。</p>
<p>You have been forced to join a race as part of a “Reality TV” show where you race through these streets, starting at the Sz´echenyi thermal bath (s for short) and ending at the Tomb of G¨ ul Baba (t for short).</p>
<p>你被强制要求参加一个赛跑作为一个TV秀的一部分节目，比赛中你需要穿越这些街道，从s开始，到t结束。</p>
<p>Naturally, you want to complete the race as quickly as possible, because you will get more promo- tional contracts the better you perform.</p>
<p>很自然的，你想要尽快的完成比赛，因为你的比赛完成的越好，你就能得到更多的商业促销合同。</p>
<p>However, there is a catch: any person who is smart enough to take a shortest s-t route will be thrown into the P´alv¨olgyi cave system and kept as a national treasure. You would like to avoid this fate, but still be as fast as possible. Write a program that computes a strictly-second-shortest s-t route.</p>
<p>但是，有一个需要了解的是，如果有人过于聪明找到从s到t的最短路线，那么他就被扔到国家极品人类保护系统中作为一个国家宝藏收藏起来。你显然要避免这种事情的发生，但是也想越快越好。写一个程序来计算一个从s到t的严格次短路线吧。</p>
<p><span style="">Sometimes the strictly-second-shortest route visits some nodes more than once; see Sample Input 2 for an example.</span></p>
<p><span style="">有的时候，严格次短路线可能访问某些节点不止一次。样例2是一个例子。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line will have the format N M, where N is the number of nodes in Budapest and M is the number of edges. The nodes are 1,2,...,N; node 1 represents s; node N represents t. Then there are M lines of the form A B L, indicating a one-way street from A to B of length L. You can assume that A != B on these lines, and that the ordered pairs (A,B) are distinct.</p>
<p>第一行包含两个整数N和M，N代表布达佩斯的节点个数，M代表边的个数。节点编号从1到N。1代表出发点s，N代表终点t。接下来的M行每行三个整数A B L，代表有一条从A到B的长度为L的单向同路。你可以认为A不等于B，也不会有重复的(A,B)对。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Output the length of a strictly-second-shortest route from s to t. If there are less than two possible lengths for routes from s to t, output &minus;1.</p>
<p>输出从s到t的严格次短路的长度。如果从s到t的路少于2条，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：</p>
<p>4 6</p>
<p>1 2 5</p>
<p>1 3 5</p>
<p>2 3 1</p>
<p>2 4 5</p>
<p>3 4 5</p>
<p>1 4 13</p>
<p>样例输入2：</p>
<p>2 2</p>
<p>1 2 1</p>
<p>2 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1：</p>
<p>11</p>
<p>样例输出2：</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于样例1：</p>
<p>There are two shortest routes of length 10 (1 → 2 → 4,1 → 3 → 4) and the strictly-second- shortest route is 1 → 2 → 3 → 4 with length 11.</p>
<p>对于样例2：</p>
<p>The shortest route is 1 → 2 of length 1, and the strictly-second route is 1 → 2 → 1 → 2 of length 3.</p>
</div>
</div>