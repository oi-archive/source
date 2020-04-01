
# Description

<div class="content"><div>小豆参加了NOI的游园会，会场上每完成一个项目就会获得一个奖章，奖章  只会是N, O, I的字样。在会场上他收集到了K个奖章组成的串。</div>
<div>兑奖规则是奖章串和兑奖串的最长公共子序列长度为小豆最后奖励的等级。</div>
<div>现在已知兑奖串长度为N，并且在兑奖串上不会出现连续三个奖章为NOI，即奖章中不会出现子串NOI。</div>
<div>现在小豆想知道各个奖励等级会对应多少个不同的合法兑奖串。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数，N，K分别代表兑奖串的长度，小豆收集的奖章串的长度。</div>
<div>第二行一共K个字符，表示小豆得到奖章串。</div>
<div>N&lt;=1000 &amp; K&lt;=15</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一共K+1行，第i行表示小豆最后奖励等级为i-1的不同的合法兑奖串的个数，可能这个数会很大，结果对10^9 + 7取模。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
NO</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
19<br/>
6<br/>
提示<br/>
最长公共子序列长度0的串有:III;<br/>
最长公共子序列长度2的串有:NON, NNO, NOO, ONO,<br/>
INO, NIO;<br/>
除去NOI，余下的19(26-6-1)种为最长公共子序列长度为1。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

