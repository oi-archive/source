# 题目描述


<p>
Time Limit : 1000 MS 
</p>
<p>
Memory Limit : 65536 KB
</p>
<p>
<br/>
</p>
<p>
Pair-Pair
</p>
<p>
Bobo is tired of all kinds of hard LIS (Longest Increasing Subsequence) problems, so he decides to make himself some easier one.
</p>
<p>
Bobo has n pairs (a1,b1),(a2,b2),…,(an,bn) where 1≤ai,bi≤m holds for all i. He defines f(i,j) be the length of longest increasing subsequence of sequence {ai,bi,aj,bj}.
</p>
<p>
It&#39;s clear that 1≤f(i,j)≤4. Bobo would like to know g(k) which is the number of pairs (i,j) where f(i,j)=k.
</p>
<p>
Note that a sequence labeled with {i1,i2,…,ik} is an increasing subsequence of {a1,a2,…,an} only if:
</p>
<p>
1≤i1&lt;i2&lt;⋯&lt;ik≤nai1&lt;ai2&lt;⋯&lt;aik
</p>
<p>
Input
</p>
<p>
The first line contains 2 integers n,m (1≤n≤105,1≤m≤103).
</p>
<p>
The i-th of the following n lines contains 2 integers ai,bi (1≤ai,bi≤m).
</p>
<p>
Output
</p>
<p>
For each set, 4 integers g(1),g(2),g(3),g(4).
</p>
<p>
Sample Input
</p>
<p>
<br/>
</p>
<p>
2 4
</p>
<p>
1 2
</p>
<p>
3 4
</p>
<p>
2 1
</p>
<p>
1 1
</p>
<p>
1 1
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
Sample Output
</p>
<p>
<br/>
</p>
<p>
0 3 0 1
</p>
<p>
4 0 0 0
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
