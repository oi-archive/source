
# Description

<div class="content"><div>众所周知，香山的红叶非常著名。然而，CTSC 举行的时间是在 5 月，而红叶的季节是秋天，所以这个季节是看不</div>
<div>到红叶的，于是我们在 CTSC 比赛中就只能讨论香山的树了。s-quark 很喜欢这些树，他计划在每棵树上贴一个各</div>
<div>不相同的标签。每个标签为条形，可以在树干上绕成一圈。为了区分每一棵树，s-quark 在每个标签上印了一个由</div>
<div>小写英文字母组成的字符串。由于树干周长的限制，标签的长度也是有限的，因此这个字符串至多只能由N个字母</div>
<div>组成。但是，由于标签是在树干上围成一圈的，所以当标签在树上贴好以后，就不再能找到标签的起始位置了。所</div>
<div>以，如果两棵树上的标签循环同构，例如分别为 &#34;abc&#34; 和 &#34;cab&#34; ，那么这两棵树就不再能通过标签区分了。针对</div>
<div>这个问题，s-quark 想了一个巧妙的办法。对于一个已经在树上贴好的标签，s-quark 规定它的起始位置必须是能</div>
<div>够使得字符串的字典序最小的起始位，即如果看到的字符串是 &#34;aba&#34;，那么就可以推断出从正确的起始位置开始看</div>
<div>到的字符串应为 &#34;aab&#34;。另外，对于有些标签，例如 &#34;abab&#34;，尽管符合字典序最小的规则，但是这样的起始位置</div>
<div>不唯一，s-quark 认为这种情况也是不理想的。所以，这样的标签 s-quark 也会避免使用。s-quark 已经把所有</div>
<div>的树都编好了顺序，准备在第一棵树上贴标签 &#34;a&#34;，之后按照字典序给每棵树贴上不同的标签。以 n=3 为例，s-q</div>
<div>uark将依次使用这些标签来标记这些树木：a, aab, aac, …, aaz, ab, abb, …, abz, ac, …s-quark 知道，香</div>
<div>山上的树总共有 K 棵。他想知道他将在最后一棵树上贴的标签是什么。但是，这个问题显然太简单了。现在，s-q</div>
<div>uark 要问你，如果他在第一棵树上贴的标签是字符串 S，那么他将在最后一棵树上贴的标签是什么呢？</div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行两个正整数 N 和 K，分别为字符串的长度和树的总数。</div>
<div>第二行一个由小写英文字母组成的字符串 S，表示在第一棵树上所贴的标签。</div>
<div>S 的长度不超过 N，并且保证是一个合法的标签。</div>
<div>1≤N≤50 &amp;&amp; 1≤K≤10^15</div>
<p></p></div>

# Output

<div class="content"><div>输出仅一行，输出一个字符串 T，表示 s-quark 将在最后一棵树上贴的标签，</div>
<div>或输出 -1，表示剩余的合法标签数量不足以贴完所有的树。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Case#1: <br/>
3 10<br/>
a<br/>
<br/>
Case#2: <br/>
3 10<br/>
xy<br/>
<br/>
Case#3: <br/>
1 100<br/>
a<br/>
<br/>
Case#4: <br/>
25 1000000000000000<br/>
u</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case#1: <br/>
aaj<br/>
<br/>
Case#2: <br/>
yzz<br/>
<br/>
Case#3: <br/>
-1<br/>
<br/>
Case#4：<br/>
uuuuuvxzuxvwwyzzuyzvxuvxw<br/>
<br/>
*以上Case#1~Case#4 分别为一个单独的样例。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

