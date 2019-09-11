# 题目描述


<h3>
【题目描述】
</h3>
<p>
The cows, who always have an inferiority complex about their
intelligence, have a new guessing game to sharpen their brains.
</p>
<p>
A designated &#39;Hay Cow&#39; hides behind the barn and creates N (1 &lt;= N
&lt;= 1,000,000) uniquely-sized stacks (conveniently numbered 1..N)
of hay bales, each with 1..1,000,000,000 bales of hay.
</p>
<p>
The other cows then ask the Hay Cow a series of Q (1 &lt;= Q &lt;= 25,000)
questions about the the stacks, all having the same form:
  What is the smallest number of bales of any stack in the range
  of stack numbers Ql..Qh (1 &lt;= Ql &lt;= N; Ql &lt;= Qh &lt;= N)?
</p>
<p>
The Hay Cow answers each of these queries with a single integer A
whose truthfulness is not guaranteed.
</p>
<p>
Help the other cows determine if the answers given by the Hay Cow
are self-consistent or if certain answers contradict others.
</p>
<h3>
PROBLEM NAME: usaco_bales
</h3>
<h3>
INPUT FORMAT:
</h3>
<p>
* Line 1: Two space-separated integers: N and Q
</p>
<p>
* Lines 2..Q+1: Each line contains three space-separated integers that represent a single query and its reply: Ql, Qh, and A
</p>
<h3>
SAMPLE INPUT (file usaco_bales.in):
</h3>
<p>
20 4
</p>
<p>
1 10 7
</p>
<p>
5 19 7
</p>
<p>
3 12 8
</p>
<p>
11 15 12
</p>
<h3>
INPUT DETAILS:
</h3>
<p>
The minimum number of bales in stacks 1..10 is 7, the minimum number
of bales in stacks 5..19 is 7, the minimum number of bales in stacks
3..12 is 8, and the minimum number of bales in stacks 11..15 is 12.
</p>
<h3>
OUTPUT FORMAT:
</h3>
<p>
* Line 1: Print the single integer 0 if there are no inconsistencies among the replies (i.e., if there exists a valid realization of the hay stacks that agrees with all Q queries).
</p>
<p>
Otherwise, print the index from 1..Q of the earliest query whose answer is inconsistent with the answers to the queries before it.
</p>
<h3>
SAMPLE OUTPUT (file usaco_bales.out):
</h3>
<p>
3
</p>
<h3>
OUTPUT DETAILS:
</h3>
<p>
Query 3 (&#34;3 12 8&#34;) is the first that is inconsistent with those
before it.
</p>
<p>
From queries 1 and 2 and the fact that all hay stacks
have a distinct number of bales, we deduce that one of stacks 5..10
must contain exactly 7 bales.
</p>
<p>
However, this stack contradicts the answer to query 3.
</p>
