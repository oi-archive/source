
# Description

<div class="content"><div>再过几天就是Alice的生日了！Alice决定举办一个生日宴会，并想邀请她的好朋友们参加宴会。Alice是个很有魅</div>
<div>力的人，她一共有N个好朋友。而她的这些好朋友互相之间可能认识，也可能不认识，还可能有矛盾。这N个人之间</div>
<div>是否认识是无所谓的，但是如果两个人之间存在矛盾就会产生一些问题。这里，矛盾关系是双向的。Alice知道，</div>
<div>如果她邀请的任意一个好朋友小X在宴会上仅看到一个与小X有矛盾的人小Y，就会不太高兴，不过可以假装没看见</div>
<div>。但是，如果小X再次看到另一个与小X有矛盾的人小Z，小X就会很生气并离开宴会。为了防止这样的情形出现，Al</div>
<div>ice决定只邀请她的一部分好朋友参加宴会，使得对于这些人中的任意一个人，至多有一个与他（或她）有矛盾的</div>
<div>人同时受到邀请。这样，就不会有人中途离开宴会了。经过调查，Alice已经掌握了在她的N个好朋友中有哪些人之</div>
<div>间存在矛盾。在保证上述原则的前提下，她希望邀请尽量多的好朋友参加宴会。请你帮助Alice计算出她最多邀请</div>
<div>多少个好朋友参加这个宴会。</div>
<div>注意，输入文件包含多组测试数据。</div></div>

# Input

<div class="content"><div>
<div>第一行包含一个正整数T,表示有T组测试数据。</div>
<div>接下来依次是T组测试数据。每组测试数据的第一行包含一个正整数N,表示Alice的好朋友数目。</div>
<div>接下来N行,每行一个长度为N的字符串。</div>
<div>其中第i个字符串Str[i]的第j个字符Str[i][j]表示第i个人和第j人是否有矛盾。</div>
<div>若Str[i][j]=‘Y’则表示i和j有矛盾;否则的话,Str[i][j]=‘N’,表示没有矛盾。</div>
<div>数据保证对于任意1≤i,j≤N,有Str[i][j]=Str[j][i];</div>
<div>对于任意1≤i≤N,有Str[i][i]=‘N’</div>
<div>1≤N≤40,0≤M≤780,1≤T≤50。</div>
</div></div>

# Output

<div class="content"><p>输出 T行，每行一个整数，依次表示每组测试数据的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
3 <br/>
NYY<br/>
YNY <br/>
YYN <br/>
6 <br/>
NYYNNN <br/>
YNYNYN <br/>
YYNYYY <br/>
NNYNNN <br/>
NYYNNY <br/>
NNYNYN <br/>
4 <br/>
NNYN <br/>
NNNY <br/>
YNNN <br/>
NYNN <br/>
7 <br/>
NNNNNNN <br/>
NNNNYNY <br/>
NNNYYYY <br/>
NNYNNYY <br/>
NYYNNNN <br/>
NNYYNNN <br/>
NYYYNNN<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 <br/>
4 <br/>
4 <br/>
5 <br/>
//【样例解释】<br/>
第1组数据：3个人两两之间都有矛盾，所以最多同时邀请两个人。<br/>
第2组数据：一个可行的最优方案是邀请编号为1、4、5、6的朋友。<br/>
第3组数据：每个人恰好和一个人有矛盾，因此可以邀请所有人。<br/>
第4组数据：最优方案是唯一的，即邀请编号为1、2、4、5、6的朋友。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

