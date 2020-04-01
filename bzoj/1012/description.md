
# Description

<div class="content"><p>　　现在请求你维护一个数列，要求提供以下两种操作：1、 查询操作。语法：Q L 功能：查询当前数列中末尾L<br/>
个数中的最大的数，并输出这个数的值。限制：L不超过当前数列的长度。2、 插入操作。语法：A n 功能：将n加<br/>
上t，其中t是最近一次查询操作的答案（如果还未执行过查询操作，则t=0)，并将所得结果对一个固定的常数D取<br/>
模，将所得答案插入到数列的末尾。限制：n是非负整数并且在长整范围内。注意：初始时数列是空的，没有一个<br/>
数。</p></div>

# Input

<div class="content"><p>　　第一行两个整数，M和D，其中M表示操作的个数(M &lt;= 200,000)，D如上文中所述，满足D在longint内。接下来<br/>
M行，查询操作或者插入操作。</p></div>

# Output

<div class="content"><p>　　对于每一个询问操作，输出一行。该行只有一个数，即序列中最后L个数的最大数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 100<br/>
A 96<br/>
Q 1<br/>
A 97<br/>
Q 1<br/>
Q 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">96<br/>
93<br/>
96</span></div>

# Hint

<div class="content"><p></p><p>　　数据如下http://pan.baidu.com/s/1i4JxCH3</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

