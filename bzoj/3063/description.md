
# Description

<div class="content"><p><span style="font-size: medium">After escaping from the farm, Bessie has decided to start a travel agency along the Amoozon river. There are several tourist sites located on both sides of the river, each with an integer value indicating how interesting the tourist site is. Tourist sites are connected by routes that cross the river (i.e., there are no routes connecting a site with a site on the same side of the river). Bessie wants to design a tour for her customers and needs your help. A tour is a sequence of tourist sites with adjacent sites connected by a route. In order to best serve her customers she wants to find the route that maximizes the sum of the values associated with each visited site. However, Bessie may be running several of these tours at the same time. Therefore it&#39;s important that no two routes on a tour intersect. Two routes (a &lt;-&gt; x) and (b &lt;-&gt; y) intersect if and only if (a &lt; b and y &lt; x) or (b &lt; a and x &lt; y) or (a = b and x = y). Help Bessie find the best tour for her agency. Bessie may start and end at any site on either side of the Amoozon.</span></p>
<p></p>
<div><span style="font-size: 12pt">  </span><span style="font-size: 12pt">在一条蛋疼的河两旁有一些景点。河左边有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个景点，河右边有</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">个景点。在河上搭着一些桥沟通两岸的景点（桥是无向的），但是在河的同一边的景点之间都有参天的大树阻拦着，无法通行。我们从河的上游往下游按顺序把景点编上号。目前我们要设计</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">条路线，可以从河岸任意一边的任意一个景点开始到河岸任意一边的任意一个景点结束。这条路线必须要满足其中没有桥交叉。我们对于交叉的定义如下：对于</span><span style="font-size: 12pt">a&lt;-&gt;x</span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">b&lt;-&gt;y</span><span style="font-size: 12pt">两座桥，若</span><span style="font-size: 12pt">(a&lt;b &amp;&amp; x&gt;y) || (a&gt;b &amp;&amp; x&lt;y) || (a=b &amp;&amp; x=y)</span><span style="font-size: 12pt">，则这两座桥交叉。满足上面的条件之后，开始提问了：已知每个景点都有一个美丽值，你设计的路线必须满足其美丽值最大。那么最大的美丽值是多少？</span></div></div>

# Input

<div class="content"><p><font size="4">* Line 1: Three space separated integers N (1 &lt;= N &lt;= 40,000), M (1 &lt;= M &lt;= 40,000), and R (0 &lt;= R &lt;= 100,000) indicating respectively the number of sites on the left side of the river, the number of sites on the right side of the river, and the number of routes. </font></p>
<p><font size="4">* Lines 2..N+1: The (i+1)th line has a single integer, L_i (0 &lt;= L_i &lt;= 40,000), indicating the value of the ith tourist site on the left side of the river. </font></p>
<p><font size="4">* Lines N+2..N+M+1: The (i+N+1)th line has a single integer, R_i (0 &lt;= R_i &lt;= 40,000), indicating the value of the ith tourist site on the right side of the river.</font></p>
<p><font size="4">* Lines N+M+2..N+M+R+1: Each line contains two space separated integers I (1 &lt;= I &lt;= N) and J (1 &lt;= J &lt;= M) indicating there is a bidirectional route between site I on the left side of the river and site J on the right side of the river. </font></p></div>

# Output

<div class="content"><p><span style="font-size: medium">Line 1: A single integer indicating the maximum sum of values attainable on a tour. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 4<br/>
1<br/>
1<br/>
5<br/>
2<br/>
2<br/>
1 1<br/>
2 1<br/>
3 1<br/>
2 2<br/>
<br/>
INPUT DETAILS: There are three sites on the left side of the Amoozon with values 1, 1, and 5. There are two sites on the right side of the Amoozon with values 2 and 2. There are four routes connecting sites on both sides of the river. </span></div>

# Sample Output

<div class="content"><span class="sampledata"> 8 <br/>
OUTPUT DETAILS: The optimal tour goes from site 1 on the left, site 1 on the right, and ends at site 3 on the left. These respectively have values 1, 2, and 5 giving a total value of the trip of 8.<br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><p> Left No.1 -&gt; Right No.1 -&gt; Left No.3，答案是1+2+5=8.</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

