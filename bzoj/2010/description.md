
# Description

<div class="content">为保证会场安全，专家确定了每一行每一列的保镖数，这个信息以一种压缩的形式给出。确定是否有可能实现这样一种方案，在每行每列安排确定数量的保镖。假设座位最初都是空的，也就是说保安可以被安排在任意一个座位上。 
题目等价于已知一个01矩阵的每行、每列各有多少个1，问这样的矩阵是否存在。
输入数据归纳为：
有R个正整数对 A1、B1，A2 、B2，……， AR、BR 
表示这个01矩阵一共有 B1+B2+…+BR行，其中有Bi 个行都含有 Ai个1。
同样的，有C个正整数对 Pi和Qi 来表示列的信息。
限制条件：按行和按列计算的总保镖数相等</div>

# Input

<div class="content">The input begins with the description of the rows. The first line of the input contains one positive integer R: the
number of groups of rows. R lines follow. Each of these lines contains 2 positive integers: the required number
of bodyguards in each row of the group and the number of rows that form the group.
This is followed by the description of column groups. The next line contains one positive integer C: the number
of groups of columns. C lines follow. Each of these lines contains 2 positive integers: the required number of
bodyguards in each column of the group and the number of columns that form the group.

You may assume that the total number of bodyguards required by row constrains is the same as the total
number of bodyguards required by column constraints. You may assume that this total number of bodyguards
is at most 10^18.
You may assume that all numbers are positive integers that do not exceed 10^9 .
You may assume 1&lt;= R,C &lt;= 200000 that  .
Several batches of test cases, worth a total of 50 points, satisfy the following criteria:
the total number of rows in the auditorium will be at most 2000
the total number of columns in the auditorium will be at most 2000
the total number of bodyguards will be at most  .
</div>

# Output

<div class="content">Output a single line with the number &#34;1&#34; if the constraints are satisfiable and the number &#34;0&#34; otherwise (quotes
for clarity).</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 1<br/>
1 2<br/>
1<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

