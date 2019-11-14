
# Description

<div class="content"><div>给定四种对字符串 S 的操作：</div>
<div>(1) push_back( P )：在 S 后连接一个字符串 P，即 S = S + P，代价为| P |；</div>
<div>(2) push_front( P )：在 S 前连接一个字符串 P，即 S = P + S，代价为| P |；</div>
<div>(3) symmetry_back( )：将 S 翻转后连接在 S 之后，即 S = S + rev(S)，代价为 1；</div>
<div>(4) symmetry_front( )：将 S 翻转后连接在 S 之前，即 S = rev(S) + S，代价为 1；</div>
<div>给定一个目标串 S，要求你通过上述四种操作，用最少的代价合成出目标串。初始只有一个空串。</div>
<div> </div></div>

# Input

<div class="content"><div>第一行一个正整数 T，表示数据组数。接下来 T 行，每组数据一行，为字符串 S。</div>
<div>1 &lt;= |S| &lt;= 100000， T &lt;= 10</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">每组数据一行输出一个正整数,Cost表示最少的代价</div></div>

# Sample Input

<div class="content"><span class="sampledata">7 <br/>
c<br/>
aaaab<br/>
bbaaaacc<br/>
ababa<br/>
abba<br/>
baab<br/>
aaabacdbbdcabaaaaaaaaaaaab</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
4 <br/>
7 <br/>
5 <br/>
3 <br/>
3<br/>
18<br/>
//{} -&gt; c，代价为 1<br/>
{} -&gt; aa -&gt; aaaa -&gt; aaaab，代价为 2 + 1 + 1 = 4<br/>
{} -&gt; aa -&gt; aaaa -&gt; aaaacc -&gt; bbaaaac，代价为 2 + 1 + 2 + 2 = 7<br/>
{} -&gt; ababa，代价为 5<br/>
{} -&gt; ab -&gt; abba，代价为 2 + 1 = 3<br/>
{} -&gt; ab -&gt; baab，代价为 2 + 1 = 3<br/>
{} -&gt; aaa -&gt; aaaaaa -&gt; baaaaaa -&gt; baaaaaaaaaaaab -&gt; aaabacdbbdcabaaaaaaaaaaaab，<br/>
代价为 3 + 1 + 1 + 1 + 12 = 18<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

