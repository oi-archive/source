
# Description

<div class="content"><p>给定一篇文章T和一个单词P，你希望知道是否可以通过从T中删除一些字母得到P。比如，单词programming可以得到pong或者program或者roaming，但是得不到map。保证所有单词只包含英文小写字母。</p>
<div>然而文章T通过一种等价形式进行了加密。等式使用一些特殊的符号（由大写字母组成），每个符号都用来表示一个由小写字母组成的单词。每个等式都满足下面之一的形式：</div>
<div>A = 由小写字母组成的单词</div>
<div>或</div>
<div>A = B + C</div>
<div>其中A, B, C可以表示任何特殊的符号，而 + 号表示单词的拼接。这种等价形式是：</div>
<div>明确的——对于每个固定的符号A，只有一个A在等式的左边（A在左边只出现一次）。</div>
<div>无环的——如果你从任意的符号A开始做等价替换，你永远不会得到一个替换过A的表达式还包含A。</div>
<div>这样的等价形式总是只有唯一解。例如，当等价形式是这样的：</div>
<div>START = FIRST + SECND</div>
<div>FIRST = D + E</div>
<div>SECND = F + E</div>
<div>D = good</div>
<div>E = times</div>
<div>F = bad</div>
<div>则符号START加密了单词goodtimesbadtimes。</div>
<div>给定一个单词P，一些等式，和一个特别的符号S，请你计算S所加密的单词是否能得到P。</div></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。每组数据第一行有一个正整数k，表示有k个等式，1 &lt;= k &lt;= 500。接下来k行，每行一个等式，等式里的字符串由空格隔开，每个字符串长度不超过5。接下来一行包含一个特殊符号S（一个大写字母组成的单词）。再接下来一行包含一个非空的由小写字母组成的单词P，P的长度不超过2000。</p>
<p></p></div>

# Output

<div class="content"><p>对于每组数据输出一行，若能，输出&#34;YES&#34;，否则输出&#34;NO&#34;。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
6<br/>
START = FIRST + SECND<br/>
FIRST = D + E<br/>
SECND = F + E<br/>
D = good<br/>
E = times<br/>
F = bad<br/>
START<br/>
debate <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

