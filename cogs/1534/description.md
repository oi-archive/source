

# 中文题意



# x



# 题目描述


<div class="ptx" lang="zh-CN">
You are working for Macrohard company in data structures department. After failing your previous task about key insertion you were asked to write a new data structure that would be able to return quickly k-th order statistics in the array segment. <br/>
That is, given an array a[1...n] of different integer numbers, your program must answer a series of questions Q(i, j, k) in the form: &#34;What would be the k-th number in a[i...j] segment, if this segment was sorted?&#34; <br/>
For example, consider the array a = (1, 5, 2, 6, 3, 7, 4). Let the question be Q(2, 5, 3). The segment a[2...5] is (5, 2, 6, 3). If we sort this segment, we get (2, 3, 5, 6), the third number is 5, and therefore the answer to the question is 5.
</div>

# 输入格式


<div class="ptx" lang="zh-CN">
The first line of the input file contains n --- the size of the array, and m --- the number of questions to answer (1 &lt;= n &lt;= 100 000, 1 &lt;= m &lt;= 5 000). <br/>
The second line contains n different integer numbers not exceeding 10<sup>9</sup> by their absolute values --- the array for which the answers should be given. <br/>
The following m lines contain question descriptions, each description consists of three numbers: i, j, and k (1 &lt;= i &lt;= j &lt;= n, 1 &lt;= k &lt;= j - i + 1) and represents the question Q(i, j, k).
</div>

# 输出格式


<div class="ptx" lang="zh-CN">
For each question output the answer to it --- the k-th number in sorted a[i...j] segment.
</div>

# 样例输入


<pre class="sio">7 3
1 5 2 6 3 7 4
2 5 3
4 4 1
1 7 3</pre>

# 样例输出


<pre class="sio">5
6
3</pre>

# 提示


<div class="ptx" lang="zh-CN">
This problem has huge input,so please use c-style input(scanf,printf),or you may got time limit exceed.
</div>

# 来源


<div class="ptx" lang="zh-CN">
<a href="http://neerc.ifmo.ru/subregions/northern.html" target="_blank">Northeastern Europe 2004, Northern Subregion</a> 
</div>

# 题目来源


<a href="http://www.poj.org/problem?id=2104&amp;lang=zh-CN&amp;change=true"> 北京大学 POJ 2104</a>
