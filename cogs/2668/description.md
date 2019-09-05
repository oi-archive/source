# 题目描述


<h3>
【题目描述】<br/>
</h3>
<p>
<br/>
</p>
<p>
A ring is compose of n circles as shown in diagram. Put natural number 1, 2, ..., n into each circle separately, and the sum of numbers in two adjacent circles should be a prime.
</p>
<p>
多组样例，按照
</p>
<p>
Case i：
</p>
<p>
·······
</p>
<p>
·······
</p>
<p>
·
</p>
<p>
·
</p>
<p>
·
</p>
<p>
<br/>
</p>
<p>
Case i+1：
</p>
<p>
··········
</p>
<p>
··········
</p>
<p>
·
</p>
<p>
·
</p>
<p>
·
</p>
<p>
<br/>
</p>
<p>
·
</p>
<p>
·
</p>
<p>
·
</p>
<p>
·
</p>
<p>
输出。
</p>
<p>
Note: the number of first circle should always be 1.
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
多个n (0 &lt; n &lt; 20).不超过6组
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
The output format is shown as sample below. Each row represents a series of circle numbers in the ring beginning from 1 clockwisely and anticlockwisely. The order of numbers must satisfy the above requirements. Print solutions in lexicographical order.
</p>
<p>
<br/>
</p>
<p>
You are to write a program that completes above process.
</p>
<p>
<br/>
</p>
<p>
Print a blank line after each case.
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
6
</p>

<p>
8
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
Case 1:
</p>

<p>
1 4 3 2 5 6
</p>

<p>
1 6 5 2 3 4
</p>

<p>
Case 2:
</p>

<p>
1 2 3 8 5 6 7 4
</p>

<p>
1 2 5 8 3 4 7 6
</p>

<p>
1 4 7 6 5 8 3 2
</p>

<p>
1 6 7 4 3 8 5 2
</p>
</pre>
<h3>
【提示】
</h3>
<p>
回溯。。。
</p>
<h3>
【来源】
</h3>
<p>
hzoi-cosmosMeta CYH
</p>
