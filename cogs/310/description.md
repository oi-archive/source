# 题目描述


<p>
	Description
</p>
<div>
	The cows have run out of hay, a horrible event that must be remedied immediately. Bessie intends to visit the other farms to survey their hay situation. There are N (2 &lt;= N &lt;= 2,000) farms (numbered 1..N); Bessie starts at Farm 1. She&#39;ll traverse some or all of the M (1 &lt;= M &lt;= 10,000) two-way roads whose length does not exceed 1,000,000,000 that connect the farms. Some farms may be multiply connected with different length roads. All farms are connected one way or another to Farm 1. <br/>
<br/>
Bessie is trying to decide how large a waterskin she will need. She knows that she needs one ounce of water for each unit of length of a road. Since she can get more water at each farm, she&#39;s only concerned about the length of the longest road. Of course, she plans her route between farms such that she minimizes the amount of water she must carry. <br/>
<br/>
Help Bessie know the largest amount of water she will ever have to carry: what is the length of longest road she&#39;ll have to travel between any two farms, presuming she chooses routes that minimize that number? This means, of course, that she might backtrack over a road in order to minimize the length of the longest road she&#39;ll have to traverse.
</div>
<p>
	Input
</p>
<div>
	* Line 1: Two space-separated integers, N and M. <br/>
<br/>
* Lines 2..1+M: Line i+1 contains three space-separated integers, A_i, B_i, and L_i, describing a road from A_i to B_i of length L_i.
</div>
<p>
	Output
</p>
<div>
	* Line 1: A single integer that is the length of the longest road required to be traversed.
</div>
<p>
	Sample Input
</p>
<pre class="sio">3 3
1 2 23
2 3 1000
1 3 43</pre>
<p>
	Sample Output
</p>
<pre class="sio">43</pre>
<p>
	Hint
</p>
<div>
	OUTPUT DETAILS: <br/>
<br/>
In order to reach farm 2, Bessie travels along a road of length 23. To reach farm 3, Bessie travels along a road of length 43. With capacity 43, she can travel along these roads provided that she refills her tank to maximum capacity before she starts down a road.
</div>
