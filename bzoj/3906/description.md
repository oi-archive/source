
# Description

<div class="content"><p><img width="1229" height="499" src="/source/bzoj/3906/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy92Mi5QTkc=.PNG" alt=""/></p></div>

# Input

<div class="content"><p>The first line contains an integer T (T ≤ 5), denoting the number of the test cases.For each test case, the first line contains an integer n(1 ≤ n ≤ 105).From the second to the n-th line, this n - 1 lines describe Bob&#39; s Trie. The i-th line contains an integer u(u &lt; i), and a lowercase letter c, which means that the father of node i is node u and the character on that edge is c. We ensure that for each node i, letters on edges connecting i and its children are all different.The next line contains an integer m(m ≤ 105), which means there are m operations.The next m lines describe all operations. In each line, the first integer indicates the type of this operation. 1 means Bob will add a new trait and 2 means Bob is asking you a question. The second integer k is the size of set P , and the next k integers are the elements of P. We ensure that these k integers are different, and they are all between 1 and n. The total size of the m sets will not be larger than 5*10^5.</p></div>

# Output

<div class="content"><p>For each test case, output the answer for each query operation, one answer in a line.</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
6<br/>
1 a<br/>
1 b<br/>
1 c<br/>
3 a<br/>
3 b<br/>
5<br/>
1 2 3 4<br/>
2 2 5 6<br/>
1 2 2 3<br/>
2 2 4 5<br/>
2 1 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014 Asia AnShan Regional Contest">2014 Asia AnShan Regional Contest</a></p></div>

