
# Description

<div class="content"><p><span style="font-size: medium">我们的小朋友很喜欢计算机科学，而且尤其喜欢二叉树。<br/>
考虑一个含有n个互异正整数的序列c[1],c[2],...,c[n]。如果一棵带点权的有根二叉树满足其所有顶点的权值都在集合{c[1],c[2],...,c[n]}中，我们的小朋友就会将其称作神犇的。并且他认为，一棵带点权的树的权值，是其所有顶点权值的总和。<br/>
给出一个整数m，你能对于任意的s(1&lt;=s&lt;=m)计算出权值为s的神犇二叉树的个数吗？请参照样例以更好的理解什么样的两棵二叉树会被视为不同的。<br/>
我们只需要知道答案关于998244353(7*17*2^23+1,一个质数)取模后的值。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行有2个整数 n,m(1&lt;=n&lt;=10^5; 1&lt;=m&lt;=10^5)。<br/>
第二行有n个用空格隔开的互异的整数 c[1],c[2],...,c[n]（1&lt;=c[i]&lt;=10^5)。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出m行，每行有一个整数。第i行应当含有权值恰为i的神犇二叉树的总数。请输出答案关于998244353(=7*17*2^23+1,一个质数)取模后的结果。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：<br/>
2 3<br/>
1 2<br/>
样例二：<br/>
3 10<br/>
9 4 3<br/>
样例三：<br/>
5 10<br/>
13 10 6 4 15<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例一：<br/>
1<br/>
3<br/>
9<br/>
样例二：<br/>
0<br/>
0<br/>
1<br/>
1<br/>
0<br/>
2<br/>
4<br/>
2<br/>
6<br/>
15<br/>
样例三：<br/>
0<br/>
0<br/>
0<br/>
1<br/>
0<br/>
1<br/>
0<br/>
2<br/>
0<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于第一个样例，有9个权值恰好为3的神犇二叉树：<br/><br/>
<img height="432" alt="" width="819" src="source/bzoj/3625/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNi9hLmpwZw==.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=VFleaKing &amp; pyx1997 感谢wyl8899提供中文翻译
">VFleaKing &amp; pyx1997 感谢wyl8899提供中文翻译<br/>
</a></p></div>

