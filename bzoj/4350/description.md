
# Description

<div class="content"><div>括号序列与猪猪侠又大战了起来。</div>
<div>众所周知，括号序列是一个只有(和)组成的序列，我们称一个括号</div>
<div>序列S合法，当且仅当:</div>
<div>1.( )是一个合法的括号序列。</div>
<div>2.若A是合法的括号序列，则(A)是合法的括号序列。</div>
<div>3.若A，B是合法的括号序列，则AB是合法的括号序列。</div>
<div>我们考虑match[i]表示从左往右数第i个左括号所对应的是第几个右</div>
<div>括号，现在他得到了一个长度为2n的括号序列，给了你m个信息，第i</div>
<div>个信息形如ai,bi，表示match[ai]&lt;match[bi]，要你还原这个序列。</div>
<div>但是你发现这个猪猪侠告诉你的信息，可能有多个括号序列合法；甚</div>
<div>至有可能告诉你一个不存在合法括号序列的信息！</div>
<div>你最近学了取模运算，你想知道答案对998244353(7*17*2^23+1)取</div>
<div>模的结果，这个模数是一个质数。</div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行一个正整数T,T&lt; = 5，表示数据组数。</div>
<div>对于每组数据，第一行一个n,m，n表示有几个左括号，m表示信息数。</div>
<div>接下来m行，每行两个数ai,bi，1&lt; = ai,bi&lt; = n。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>对于每组数据，输出一个数表示答案。</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 0<br/>
5 0<br/>
3 2<br/>
1 2<br/>
2 3<br/>
3 2<br/>
2 1<br/>
2 3<br/>
3 3<br/>
1 2<br/>
2 3<br/>
3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
42<br/>
1<br/>
2<br/>
0</span></div>

# Hint

<div class="content"><p></p><p> 对于前两个点，是卡特兰数的情况。</p><br/>
<div>对于第三个点，合法的情况只可能是 ()()()。</div><br/>
<div>对于第四个点，合法情况可能是 (()()) 或者 (())()</div><br/>
<div>对于第五个点，由于拓扑关系形成了环，显然无解。</div><br/>
<div></div><br/>
<div>对于 100% 的数据，保证 n &lt; = 300</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

