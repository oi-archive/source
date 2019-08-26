
# Description

<div class="content"><div style="text-indent: 15.75pt"><span style="font-size: medium">定义任意两小写字母间有一个差别值X（1&lt;=X&lt;=5），假设26个小写字母随意排列构成的都是单词，则对于一个单词可算出差别总和为sum，例如：</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">假设X[e-l]=3，X[l-y]=2，X[l-l]=1，则单词“elly”的sum值为3+1+2=6。</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">现在给出N和M，N表示sum值的上限（可以等于N），M表示已知关系个数，接下来M行，每行三个数L1，L2，F，表示字母L1到L2和L2到L1的X值都为F，若未提及的字母对则默认它们的X值为1，则问总共可形成多少符合条件的单词？</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 15.75pt"><span style="font-size: medium">第一行N,M （1&lt;=N&lt;=1000 000 000）</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">之后M行，每行三个数L1，L2，F，保证每对字母最多出现一次。</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">   符合条件的单词总数 mod 1000 000 007 的结果。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">数据范围</span></div>
<div><span style="font-size: medium">   50% N&lt;=1000 000</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium">100% N&lt;=1000 000 000   1&lt;=F&lt;=5</span></div>
<div style="text-indent: 15.75pt"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">20 10<br/>
e l 3<br/>
e o 1<br/>
o n 2<br/>
o r 4<br/>
r a 4<br/>
i n 5<br/>
e n 2<br/>
n t 3<br/>
t w 3<br/>
w i 5<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 470059518</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

