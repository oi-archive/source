
# Description

<div class="content"><div>在神秘的东方有一棵奇葩的树，它有一个固定的根节点（编号为1）。树的每条边上都是一个字符，字符为a,b,c中的一个，你可以从树上的任意一个点出发，然后沿着远离根的边往下行走，在任意一个节点停止，将你经过的边的字符依次写下来，就能得到一个字符串，例如：</div>
<div><img src="/source/bzoj/3756/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMS9jY2MuZ2lm.gif" width="213" height="244" alt=""/></div>
<div> </div>
<div>在这棵树中我们能够得到的字符串是：</div>
<div>c, cb, ca, a, b, a</div>
<div>现在pty得到了一棵树和一个字符串S。如果S的一个子串[l,r]和树上某条路径所得到的字符串完全相同，则我们称这个子串和该路径匹配。现在pty想知道，S的所有子串和树上的所有路径的匹配总数是多少？</div>
<p></p></div>

# Input

<div class="content"><div>第一行：n</div>
<div>接下来n-1行，每行一个整数fa, 一个字符c，字符和整数之间用一个空格隔开</div>
<div>第i行fa代表第i号节点的父亲，c表示第i号节点和fa的连边的字符</div>
<div>最后一行为字符串S</div>
<p></p></div>

# Output

<div class="content"><div>输出共一行，表示匹配总数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 c<br/>
2 b<br/>
1 a<br/>
2 a<br/>
cba</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
【样例说明】<br/>
单个字符匹配的对数为4对，两个字符匹配的对数为1对：cb<br/>
			<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【数据规模】</div><br/>
<div>N&lt;=800000<span class="Apple-tab-span" style="white-space:pre">	</span>树的最大深度&lt;=800000<span class="Apple-tab-span" style="white-space:pre">	</span></div><br/>
<div><span style="color: rgb(255, 0, 0);">此题存在版权，故不再支持提交，保留在此只供大家参考题面！ 望见谅！</span></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

