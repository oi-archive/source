
# Description

<div class="content">We are looking into building a very long fence. We have already found a nice place to build it, and all that remains is to collect the materials. 

From local hardware stores, we can buy unlimited numbers of wooden boards, each of which can come in a variety of different lengths. To avoid waste, we want to make sure that the total length of these boards is exactly equal to the length of the fence we are trying to build. 

Given the length of the fence, and the possible board lengths that we can use, what is the minimum number of boards that we need to purchase in order to get exactly the right length?

Beware: the fence is going to be very long!

</div>

# Input

<div class="content">The first line of the input file contains the number of cases, T. T test cases follow. 

Each test case consists of two lines. The first line contains space-separated integers L and N. These represent the total length of the fence, and the number of different board lengths that can be purchased. The second line contains N space-separated integers B1, B2, ..., BN, representing all the possible board lengths. 

</div>

# Output

<div class="content">For each test case, output one line containing &#34;Case #x: M&#34;,
 where x is the case number (starting from 1) and M is as follows: 

If it is possible to purchase one or more boards so that their total length is exactly equal to L, 
then M should be the minimum number of boards required to do this. 
Otherwise, M should be the string &#34;IMPOSSIBLE&#34;. 

Limits
1 ≤ T ≤ 50.
10^10 ≤ L ≤ 10^18.
1 ≤ N ≤ 100.
All the Bi values in a single test case are distinct.


Small dataset
1 ≤ Bi ≤ 100.


Large dataset
1 ≤ Bi ≤ 100000.

</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
10000000001 3<br/>
23 51 100<br/>
10000000001 3<br/>
100 52 22 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 100000004<br/>
Case #2: IMPOSSIBLE<br/>
<br/>
 <br/>
Explanation<br/>
In the first example, the optimal strategy is to use 2 boards of length 23, 5 boards of length 51,<br/>
 and 99999997 boards of length 100. Of course, you could use just 100000001 boards of length 100 <br/>
to get a total greater than L, but that is not allowed.<br/>
<br/>
In the second example, it is only possible to get even lengths.<br/>
</span></div>

# Hint

<div class="content"><p>鸣谢成都七中Zxytim</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 3">Round 3</a></p></div>

