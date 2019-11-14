# 题目描述


<h3>
Problem 3: Balanced Cow Breeds [Brian Dean, 2012]
</h3>
<p>
Farmer John usually brands his cows with a circular mark, but his branding
</p>
<p>
iron is broken, so he instead must settle for branding each cow with a mark
</p>
<p>
in the shape of a parenthesis -- (.  He has two breeds of cows on his farm:
</p>
<p>
Holsteins and Guernseys.  He brands each of his cows with a
</p>
<p>
parenthesis-shaped mark.  Depending on which direction the cow is facing,
</p>
<p>
this might look like either a left parenthesis or a right parenthesis.
</p>
<p>
FJ&#39;s N cows are all standing in a row, each facing an arbitrary direction,
</p>
<p>
so the marks on the cows look like a string of parentheses of length N.
</p>
<p>
Looking at this lineup, FJ sees a remarkable pattern: if he scans from left
</p>
<p>
to right through just the Holsteins (in the order they appear in the
</p>
<p>
sequence), this gives a balanced string of parentheses; moreover, the same
</p>
<p>
is true for the Guernseys!  To see if this is truly a rare event, please
</p>
<p>
help FJ compute the number of possible ways he could assign breeds to his N
</p>
<p>
cows so that this property holds.  
</p>
<p>
There are several ways to define what it means for a string of parentheses
</p>
<p>
to be &#34;balanced&#34;.  Perhaps the simplest definition is that there must be
</p>
<p>
the same total number of (&#39;s and )&#39;s, and for any prefix of the string,
</p>
<p>
there must be at least as many (&#39;s as )&#39;s.  For example, the following
</p>
<p>
strings are all balanced:
</p>
<p>
()
</p>
<p>
(())
</p>
<p>
()(()())
</p>
<p>
while these are not:
</p>
<p>
)(
</p>
<p>
())(
</p>
<p>
((())))
</p>
<h3>
PROBLEM NAME: bbreeds
</h3>
<h3>
INPUT FORMAT:
</h3>
<p>
* Line 1: A string of parentheses of length N (1 &lt;= N &lt;= 1000).
</p>
<h3>
SAMPLE INPUT (file bbreeds.in):
</h3>
<p>
(())
</p>
<h3>
OUTPUT FORMAT:
</h3>
<p>
* Line 1: A single integer, specifying the number of ways FJ can
</p>
<p>
       assign breeds to cows so that the Holsteins form a balanced
</p>
<p>
       subsequence of parentheses, and likewise for the Guernseys.
</p>
<p>
       Since the answer might be a very large number, please print
</p>
<p>
       the remainder of this number when divided by 2012 (i.e., print
</p>
<p>
       the number mod 2012).  Breed assignments involving only one
</p>
<p>
       breed type are valid.
</p>
<h3>
SAMPLE OUTPUT (file bbreeds.out):
</h3>
<p>
6
</p>
<h3>
OUTPUT DETAILS:
</h3>
<p>
The following breed assignments work:
</p>
<p>
(())
</p>
<p>
HHHH
</p>
<p>
(())
</p>
<p>
GGGG
</p>
<p>
(())
</p>
<p>
HGGH
</p>
<p>
(())
</p>
<p>
GHHG
</p>
<p>
(())
</p>
<p>
HGHG
</p>
<p>
(())
</p>
<p>
GHGH
</p>
