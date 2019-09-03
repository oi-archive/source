# 题目描述


<p>
Description
</p>
<div>
In order to get from one of the F (1 &lt;= F &lt;= 5,000) grazing fields (which are numbered 1..F) to another field, Bessie and the rest of the herd are forced to cross near the Tree of Rotten Apples. The cows are now tired of often being forced to take a particular path and want to build some new paths so that they will always have a choice of at least two separate routes between any pair of fields. They currently have at least one route between each pair of fields and want to have at least two. Of course, they can only travel on Official Paths when they move from one field to another. <br/>
<br/>
Given a description of the current set of R (F-1 &lt;= R &lt;= 10,000) paths that each connect exactly two different fields, determine the minimum number of new paths (each of which connects exactly two fields) that must be built so that there are at least two separate routes between any pair of fields. Routes are considered separate if they use none of the same paths, even if they visit the same intermediate field along the way. <br/>
<br/>
There might already be more than one paths between the same pair of fields, and you may also build a new path that connects the same fields as some other path.
</div>
<p>
Input
</p>
<div>
Line 1: Two space-separated integers: F and R <br/>
<br/>
Lines 2..R+1: Each line contains two space-separated integers which are the fields at the endpoints of some path.
</div>
<p>
Output
</p>
<div>
Line 1: A single integer that is the number of new paths that must be built.
</div>
<p>
Sample Input
</p>
<p>
<br/>
</p>
<p>
7 7
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
3 4
</p>
<p>
2 5
</p>
<p>
4 5
</p>
<p>
5 6
</p>
<p>
5 7
</p>
<p>
<br/>
</p>
<p>
Sample Output
</p>
<p>
2
</p>
<p>
Hint
</p>
<div>
Explanation of the sample: <br/>
<br/>
One visualization of the paths is: <br/>
<pre>   1   2   3
   +---+---+  
       |   |
       |   |
 6 +---+---+ 4
      / 5
     / 
    / 
 7 +</pre>
Building new paths from 1 to 6 and from 4 to 7 satisfies the conditions. <br/>
<pre>   1   2   3
   +---+---+  
   :   |   |
   :   |   |
 6 +---+---+ 4
      / 5  :
     /     :
    /      :
 7 + - - - - </pre>
Check some of the routes: <br/>
<span>1 – 2:  1 –&gt; 2 and 1 –&gt; 6 –&gt; 5 –&gt; 2 <br/>
1 – 4:  1 –&gt; 2 –&gt; 3 –&gt; 4 and 1 –&gt; 6 –&gt; 5 –&gt; 4 <br/>
3 – 7:  3 –&gt; 4 –&gt; 7 and 3 –&gt; 2 –&gt; 5 –&gt; 7</span> <br/>
Every pair of fields is, in fact, connected by two routes. <br/>
<br/>
It&#39;s possible that adding some other path will also solve the problem (like one from 6 to 7). Adding two paths, however, is the minimum.
</div>
