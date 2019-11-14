# 题目描述


<pre>Secret Message [David Benjamin and Jacob Steinhardt, 2008]

Bessie is leading the cows in an attempt to escape! To do this, the
cows are sending secret binary messages to each other.

Ever the clever counterspy, Farmer John has intercepted the first
b_i (1 &lt;= b_i &lt;= 10,000) bits of each of M (1 &lt;= M &lt;= 50,000) of
these secret binary messages.

He has compiled a list of N (1 &lt;= N &lt;= 50,000) partial codewords
that he thinks the cows are using. Sadly, he only knows the first
c_j (1 &lt;= c_j &lt;= 10,000) bits of codeword j.

For each codeword j, he wants to know how many of the intercepted
messages match that codeword (i.e., for codeword j, how many times
does a message and the codeword have the same initial bits).  Your
job is to compute this number.

The total number of bits in the input (i.e., the sum of the b_i and
the c_j) will not exceed 500,000.

Memory Limit: 32MB

POINTS: 270

PROBLEM NAME: sec

INPUT FORMAT:

* Line 1: Two integers: M and N

* Lines 2..M+1: Line i+1 describes intercepted code i with an integer
        b_i followed by b_i space-separated 0&#39;s and 1&#39;s

* Lines M+2..M+N+1: Line M+j+1 describes codeword j with an integer
        c_j followed by c_j space-separated 0&#39;s and 1&#39;s

SAMPLE INPUT (file sec.in):

4 5
3 0 1 0
1 1
3 1 0 0
3 1 1 0
1 0
1 1
2 0 1
5 0 1 0 0 1
2 1 1

INPUT DETAILS:

Four messages; five codewords.
The intercepted messages start with 010, 1, 100, and 110.
The possible codewords start with 0, 1, 01, 01001, and 11.

OUTPUT FORMAT:

* Lines 1..N: Line j: The number of messages that the jth codeword
        could match.

SAMPLE OUTPUT (file sec.out):

1
3
1
1
2

OUTPUT DETAILS:

0 matches only 010: 1 match
1 matches 1, 100, and 110: 3 matches
01 matches only 010: 1 match
01001 matches 010: 1 match
11 matches 1 and 110: 2 matches

</pre>
