
# Description

<div class="content">Farmer John and Bessie are playing games again. This one has to do
with troughs of water.

Farmer John has hidden N (1 &lt;= N &lt;= 20) troughs behind the barn,
and has filled some of them with food. Bessie has asked M (1 &lt;= M
&lt;= 100) questions of the form, &#34;How many troughs from this list
(which she recites) are filled?&#34;.

Bessie needs your help to deduce which troughs are actually filled.

Consider an example with four troughs where Bessie has asked these
questions (and received the indicated answers):

    1) &#34;How many of these troughs are filled: trough 1&#34;
       --&gt;  1 trough is filled

    2) &#34;How many of these troughs are filled: troughs 2 and 3&#34;
       --&gt;  1 trough is filled

    3) &#34;How many of these troughs are filled: troughs 1 and 4&#34;
       --&gt;  1 trough is filled

    4) &#34;How many of these troughs are filled: troughs 3 and 4&#34;
       --&gt;  1 trough is filled

From question 1, we know trough 1 is filled.
From question 3, we then know trough 4 is empty.
From question 4, we then know that trough 3 is filled.
From question 2, we then know that trough 2 is empty.

求N位二进制数X，使得给定的M个数，满足X and Bi=Ci ,Bi ci分别是读入的两个数
</div>

# Input

<div class="content">* Line 1: Two space-separated integers: N and M

* Lines 2..M+1: A subset of troughs, specified as a sequence of
        contiguous N 0&#39;s and 1&#39;s, followed by a single integer that is
        the number of troughs in the specified subset that are filled.

</div>

# Output

<div class="content">* Line 1: A single line with:

  * The string &#34;IMPOSSIBLE&#34; if there is no possible set of filled troughs 
    compatible with Farmer John&#39;s answers.

  * The string &#34;NOT UNIQUE&#34; if Bessie cannot determine from the given data 
    exactly what troughs are filled.

  * Otherwise, a sequence of contiguous N 0&#39;s and 1&#39;s specifying
    which troughs are filled.


</div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1000 1<br/>
0110 1<br/>
1001 1<br/>
0011 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1010<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

