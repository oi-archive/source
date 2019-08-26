
# Description

<div class="content">让我们考虑一个包含n 个门的电路. 门从0 到 n-1编号. 每个门都包含若干个输入和一个输出. 每一个输入和输出都只可能是0, 1 or 1/2三种状态. 每个输入都连接着某个门的输出. 输入的状态就等于它连接的输出的状态值. 每个输出可能连接着任意多个输入. 门0 和 1 是很特殊的两个门--- 门0的输出永远为0,门1的输出永远为1. 我们说一个门的输出状态是”有效的”当: 
•	a) 它的输入中0的个数多于1的个数那么输出状态为0. 
•	b) 它的输入中0的个数等于1的个数那么输出状态为1/2. 
•	c) 它的输入中0的个数少于1的个数那么输出状态为1. 
•	d) 是特殊门0和1,他们分别输出0和1. 
给出电路信息,要求确定所有可以确定状态的门的状态分别是什么. 
</div>

# Input

<div class="content">第一行一个数 n, 2 &lt;= n &lt;= 10,000. 接下来n-2 行表示门的连接信息第 i 行描述第i个门的输入端.一个数 k_i 表示它的输入端个数,接下来k_i 个数分别表示每个输入端的门的编号, k_i &gt;= 1. 所有门的输入端总数不超过200,000. 
</div>

# Output

<div class="content">输出 n 行表示n个门的输出状态: 如果确定则输出具体状态值,否则输出? .
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
5<br/>
2 0 1<br/>
2 4 2<br/>
2 2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
1/2<br/>
?<br/>
?<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Stage 2">Stage 2</a></p></div>

