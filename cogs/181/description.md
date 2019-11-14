# 题目描述


<p>
FJ&#39;s N (1 ≤ N ≤ 10,000) cows conveniently indexed 1..N are standing in a line. Each cow has a positive integer height (which is a bit of secret). You are told only the height H (1 ≤ H ≤ 1,000,000) of the tallest cow along with the index I of that cow.
</p>
<p>
FJ has made a list of R (0 ≤ R ≤ 10,000) lines of the form &#34;cow 17 sees cow 34&#34;. This means that cow 34 is at least as tall as cow 17, and that every cow between 17 and 34 has a height that is strictly smaller than that of cow 17.
</p>
<p>
For each cow from 1..N, determine its maximum possible height, such that all of the information given is still correct. It is guaranteed that it is possible to satisfy all the constraints.
</p>
<p>
<br/>
</p>
<p>
为了方便我们把FJ养的N头(1 ≤ N ≤ 10,000)奶牛从1号开始编号，一直编到N号，并且让他们站成一列。每头牛都有一个正整数用来描述她的身高(有些牛不愿意说，她们的身高保密)。你只知道这些牛中最高的那一头的身高是H，她的编号是第I号。
</p>
<p>
FJ写了一张单子，上面有R个陈述句，大概是”第17号牛可以看见第34号牛”这种。这意味着第34号牛最起码和第17号牛一样高。而且17号牛和34号牛之间的牛得身高都严格的小于min(H[17],H[34])。
</p>
<p>
从第1号牛到第N号牛，求她们可能拥有的最大身高，所给出的所有信息都是正确的。这可以保证满足所有条件。
</p>
<p>
<br/>
</p>
<p>
Input
</p>
<ul>
<li>
Line 1: Four space-separated integers: N, I, H and R
</li>
<li>
Lines 2..R + 1: Two distinct space-separated integers A and B (1 ≤ A, B ≤ N), indicating that cow A can see cow B.
</li>
</ul>
<p>
<br/>
</p>
<p>
输入：
</p>
<p>
第1行：四个由空格分开的整数，N，I，H和R。
</p>
<p>
第2..R+1行：两个由空格分开的整数A和B(1 ≤ A, B ≤ N),表示第A号牛可以看到第B号牛。
</p>
<p>
<br/>
</p>
<p>
Output
</p>
<ul>
<li>
Lines 1..N: Line i contains the maximum possible height of cow i.
</li>
</ul>
<p>
<br/>
</p>
<p>
输出：
</p>
<p>
第1..N行:第i行包括第i号牛可能拥有的最大身高。
</p>
<p>
<br/>
</p>
<p>
Sample Input
</p>
<pre>9 3 5 5
1 3
5 3
4 3
3 7
9 8
</pre>
<p>
Sample Output
</p>
<pre>5
4
5
3
4
4
5
5
5
</pre>
<p>
Input Details
</p>
<p>
There are 9 cows, and the 3rd is the tallest with height 5.
</p>
<p>
<br/>
</p>
<p>
输入细节：
</p>
<p>
由9头奶牛，第三头奶牛最高，身高是5.
</p>
译byKZFFFFFFFF
<p>
<br/>
</p>
