# 题目描述


<p>
Poor Bessie has taken a job in the convenience store located just over the border in Slobbovia. Slobbovians use different coinages than the USA; their coin values change day-by-day!
</p>
<p>
Help Bessie make optimal change for Slobbovian shoppers. You will need to create C (1 ≤ C ≤ 1000) cents of change using N (1 ≤ N ≤ 10) coins of various values. All test cases will be solvable using the supplied coins.
</p>
<p>
If 5 coins of values 50, 25, 10, 5, and 1 were available, Bessie would make optimum change (minimal coins) of 93 cents by using 1 x 50, 1 x 25, 1 x 10, 1 x 5, and 3 x 1 coins (a total of 7 coins).
</p>
<p>
How hard could it be? The final two test cases will be challenging.
</p>
<p>
<br/>
</p>
<p>
贫穷的贝茜开始在斯罗玻维亚国境上的一家便利店打工。当地居民的货币和某西方大国的是不流通的，而且他们的硬币面值每天都不一样！
</p>
<p>
帮助贝茜给斯罗玻维亚人最佳的找零方案。你需要找开C(1&lt;=C&lt;=1000)分钱，使用N(1&lt;=N&lt;=10)种不同面值的硬币，保证所有数据可解。
</p>
<p>
如果今天有五种面值的硬币可用，分别是50分，25分，10分，5分和1分，贝茜的最佳找零方案是使用最少数目的硬币。比如今天需要找93分钱，可以用1个50分硬币，1个25分硬币，1个10分硬币，1个5分硬币和3个1分硬币。(共计7枚)
</p>
<p>
注意最后两个数据会给你挖坑。
</p>
<p>
<br/>
</p>
<p>
Input
</p>
<ul>
<li>
Line 1: Two space-separate integers: C and N
</li>
</ul>
<ul>
<li>
Lines 2..N + 1: Each line contains a single unique integer that is a coin value that can be used to create change
</li>
<li>
<p>
输入：
</p>
<p>
第1行：2个由空格分开的整数C和N。
</p>
<p>
第2..N+1行：每行一个独一无二的整数表示当天可用的硬币的面值。
</p>
<br/>
</li>
</ul>
<p>
Output
</p>
<ul>
<li>
Line 1: A single integer that is the minimum number of coins to create C cents
</li>
</ul>
<p>
<br/>
</p>
<p>
输出：
</p>
<p>
第1行：一个单独的整数表示找开C分钱需要的最小硬币数。
</p>
<p>
译byKZFFFFFFFF
</p>
<p>
<br/>
</p>
<p>
Sample Input
</p>
<pre>93 5
25
50
10
1
5
</pre>
<p>
Sample Output
</p>
<pre>7 
</pre>
