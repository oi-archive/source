
# Description

<div class="content"><p><font size="3" face="Times New Roman">The N (1 &lt;= N &lt;= 20) cows conveniently numbered 1...N are playing <br/>
yet another one of their crazy games with Farmer John. The cows <br/>
will arrange themselves in a line and ask Farmer John what their <br/>
line number is. In return, Farmer John can give them a line number <br/>
and the cows must rearrange themselves into that line. <br/>
A line number is assigned by numbering all the permutations of the <br/>
line in lexicographic order. <br/>
<br/>
Consider this example: <br/>
Farmer John has 5 cows and gives them the line number of 3. <br/>
The permutations of the line in ascending lexicographic order: <br/>
1st: 1 2 3 4 5 <br/>
2nd: 1 2 3 5 4 <br/>
3rd: 1 2 4 3 5 <br/>
Therefore, the cows will line themselves in the cow line 1 2 4 3 5. <br/>
<br/>
The cows, in return, line themselves in the configuration &#34;1 2 5 3 4&#34; and <br/>
ask Farmer John what their line number is. <br/>
<br/>
Continuing with the list: <br/>
4th : 1 2 4 5 3 <br/>
5th : 1 2 5 3 4 <br/>
Farmer John can see the answer here is 5 <br/>
<br/>
Farmer John and the cows would like your help to play their game. <br/>
They have K (1 &lt;= K &lt;= 10,000) queries that they need help with. <br/>
Query i has two parts: C_i will be the command, which is either &#39;P&#39; <br/>
or &#39;Q&#39;. <br/>
<br/>
If C_i is &#39;P&#39;, then the second part of the query will be one integer <br/>
A_i (1 &lt;= A_i &lt;= N!), which is a line number. This is Farmer John <br/>
challenging the cows to line up in the correct cow line. <br/>
<br/>
If C_i is &#39;Q&#39;, then the second part of the query will be N distinct <br/>
integers B_ij (1 &lt;= B_ij &lt;= N). This will denote a cow line. These are the <br/>
cows challenging Farmer John to find their line number. <br/>
<br/>
有N头牛，分别用1……N表示，排成一行。 <br/>
将N头牛，所有可能的排列方式，按字典顺序从小到大排列起来。 <br/>
例如：有5头牛 <br/>
1st: 1 2 3 4 5 <br/>
2nd: 1 2 3 5 4 <br/>
3rd: 1 2 4 3 5 <br/>
4th : 1 2 4 5 3 <br/>
5th : 1 2 5 3 4 <br/>
…… <br/>
现在，已知N头牛的排列方式，求这种排列方式的行号。 <br/>
或者已知行号，求牛的排列方式。 <br/>
所谓行号，是指在N头牛所有可能排列方式，按字典顺序从大到小排列后，某一特定排列方式所在行的编号。 <br/>
如果，行号是3，则排列方式为1 2 4 3 5 <br/>
如果，排列方式是 1 2 5 3 4 则行号为5 <br/>
<br/>
有K次问答，第i次问答的类型，由C_i来指明，C_i要么是‘P’要么是‘Q’。 <br/>
当C_i为P时，将提供行号，让你答牛的排列方式。当C_i为Q时，将告诉你牛的排列方式，让你答行号。 <br/>
<br/>
</font></p></div>

# Input

<div class="content"><p><font size="3" face="Times New Roman">* Line 1: Two space-separated integers: N and K <br/>
* Lines 2..2*K+1: Line 2*i and 2*i+1 will contain a single query. <br/>
Line 2*i will contain just one character: &#39;Q&#39; if the cows are lining <br/>
up and asking Farmer John for their line number or &#39;P&#39; if Farmer <br/>
John gives the cows a line number. <br/>
<br/>
If the line 2*i is &#39;Q&#39;, then line 2*i+1 will contain N space-separated <br/>
integers B_ij which represent the cow line. If the line 2*i is &#39;P&#39;, <br/>
then line 2*i+1 will contain a single integer A_i which is the line <br/>
number to solve for. <br/>
<br/>
第1行：N和K <br/>
第2至2*K+1行：Line2*i ，一个字符‘P’或‘Q’，指明类型。 <br/>
如果Line2*i是P，则Line2*i+1，是一个整数，表示行号； <br/>
如果Line2*i+1 是Q ，则Line2+i，是N个空格隔开的整数，表示牛的排列方式。</font></p>
<p></p></div>

# Output

<div class="content"><p><font size="3" face="Times New Roman">* Lines 1..K: Line i will contain the answer to query i. <br/>
<br/>
If line 2*i of the input was &#39;Q&#39;, then this line will contain a <br/>
single integer, which is the line number of the cow line in line <br/>
2*i+1. <br/>
<br/>
If line 2*i of the input was &#39;P&#39;, then this line will contain N <br/>
space separated integers giving the cow line of the number in line <br/>
2*i+1. <br/>
第1至K行：如果输入Line2*i 是P，则输出牛的排列方式；如果输入Line2*i是Q，则输出行号</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
P<br/>
3<br/>
Q<br/>
1 2 5 3 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1 2 4 3 5<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

