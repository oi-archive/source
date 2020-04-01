
# Description

<div class="content"><div>首先，给定你N（1≤N≤30）个可重复的字符串（貌似都是由小写字母构成，题目也没说吧。。。），每个串的长</div>
<div>度也不超过30个字符。 Alice和Bob博弈，Alice先手，初始是空串。 每次要在串前或串后任意加一个小写字符，</div>
<div>形成当前新的字符串，使得给定的字符串中，至少存在一个串包含该新的串（即新的串为原始给定某串的子串）。</div>
<div>不能操作就输了。 对于当前新的串，题目给了个计分系统，将分数加给当前操作完生成新的串的人（自己去PDF看</div>
<div>下吧。。。），后面的注释大概意思是：1.|S|是S 的长度；2.value(c)为字母‘c’的字母表序号，即‘c’=a就</div>
<div>是1，‘c’=b就是2......‘c’=z就是26之类的，公式中的‘c’应该就是个代号；3.occ(S)表示一个字符串S在原</div>
<div>始给定字符串中是occ(S)个的字符串的子串。然后就是遵循博弈原则：自己分数尽可能高，对手分数尽可能低。这</div>
<div>是显然的。最后输出谁能获胜，并输出Alice和Bob最终得分。。。</div>
<div>原题面PDF版:<a href="http://www.lydsy.com/JudgeOnline/upload/5009.pdf">www.lydsy.com/JudgeOnline/upload/5009.pdf</a></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数N，代表字符串个数。</div>
<div>接下来N 行，每行一个字符串。</div>
<div>1≤N≤30，每个给定串的长度也不超过30个字符</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出的第一行为一个字符串，输出获胜者（即Alice OR Bob）。</div>
<div>第二行为一个空格隔开两个整数，依次代表Alice和 Bob 的得分。</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：<br/>
2 <br/>
aba <br/>
abac<br/>
<br/>
样例二：<br/>
3<br/>
artem <br/>
nik <br/>
max</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例一：<br/>
Bob <br/>
29 35<br/>
<br/>
样例二：<br/>
Alice <br/>
2403 1882</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2017年第二届CCPC全国女生赛 By 佚名上传">2017年第二届CCPC全国女生赛 By 佚名上传</a></p></div>

