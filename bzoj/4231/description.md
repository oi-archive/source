
# Description

<div class="content"><div>回忆树是树。</div>
<div>具体来说，是n个点n-1条边的无向连通图，点标号为1~n，每条边上有一个字符（出于简化目的，我们认为只有小写字母）。</div>
<div>对一棵回忆树来说，回忆当然是少不了的。</div>
<div>一次回忆是这样的：你想起过往，触及心底…唔,不对，我们要说题目。</div>
<div>这题中我们认为回忆是这样的：给定2个点u，v(u可能等于v)和一个非空字符串s，问从u到v的简单路径上的所有边按照到u的距离从小到大的顺序排列后，边上的字符依次拼接形成的字符串中给定的串s出现了多少次。</div>
<p></p></div>

# Input

<div class="content"><div>第一行2个整数，依次为树中点的个数n和回忆的次数m。</div>
<div>接下来n-1行，每行2个整数u、v和1个小写字母c，表示回忆树的点u、v之间有一条边，边上的字符为c</div>
<div>接下来2m行表示m次回忆，每次回忆2行：第1行2个整数u、v，第2行给出回忆的字符串s。</div>
<p></p></div>

# Output

<div class="content"><div>对于每次回忆，输出串s出现的次数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 3<br/>
1 2 w<br/>
2 3 w<br/>
3 4 x<br/>
4 5 w<br/>
5 6 w<br/>
6 7 x<br/>
7 8 w<br/>
8 9 w<br/>
9 10 x<br/>
10 11 w<br/>
11 12 w<br/>
1 7<br/>
wwx<br/>
1 12<br/>
www<br/>
1 12<br/>
w</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
8</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，n&lt;=100000,m&lt;=100000,询问串的总长&lt;=300000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

