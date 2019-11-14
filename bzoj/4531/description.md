
# Description

<div class="content"><p> <img src="/source/bzoj/4531/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9kZC5wbmc=.png" width="255" height="206" alt=""/></p>
<div>在一个N个节点的无向图（没有自环、重边）上，每个点都有一个符号，</div>
<div>可能是数字，也可能是加号、减号、乘号、除号、小括号。你要在这个图上数</div>
<div>一数，有多少种走恰好K个节点的方法，使得路过的符号串起来能够得到一</div>
<div>个算数表达式。路径的起点和终点可以任意选择。</div>
<div>所谓算数表达式，就是由运算符连接起来的一系列数字。括号可以插入在</div>
<div>表达式中以表明运算顺序。</div>
<div>注意，你要处理各种情况，比如数字不能有多余的前导0，减号只有前面</div>
<div>没有运算符或数字的时候才可以当成负号，括号可以任意添加（但不能有空括</div>
<div>号），0可以做除数（我们只考虑文法而不考虑语意），加号不能当正号。</div>
<div>例如，下面的是合法的表达式：</div>
<div>-0/0</div>
<div>((0)+(((2*3+4)+(-5)+7))+(-(2*3)*6))</div>
<div>而下面的不是合法的表达式：</div>
<div>001+0</div>
<div>1+2(2)</div>
<div>3+-3</div>
<div>--1</div>
<div>+1</div>
<div>()</div>
<div></div></div>

# Input

<div class="content"><div>第一行三个整数N,M,K，表示点的数量，边的数量和走的节点数。</div>
<div>第二行一个字符串，表示每个点的符号。</div>
<div>接下来M行，每行两个数，表示一条边连的两个点的编号。</div>
<div>1≤N≤20，0≤M≤N×(N-1)/2，0≤K≤30</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，表示走的方法数。这个数可能比较大，你只需要输出</div>
<div>它模1000000007的余数即可。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 10 3<br/>
)(1*+0<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
3 4<br/>
2 5<br/>
3 5<br/>
3 6<br/>
4 6<br/>
5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
//一共有10条路径，构成的表达式依次是101, (1), 1+1, 1+0, 1*1, 1*0, 0+0,<br/>
0+1, 0*0, 0*1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

