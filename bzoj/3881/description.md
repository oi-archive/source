
# Description

<div class="content"><div>Alice有n个字符串S_1,S_2...S_n，Bob有一个字符串集合T，一开始集合是空的。</div>
<div>接下来会发生q个操作，操作有两种形式：</div>
<div>“1 P”，Bob往自己的集合里添加了一个字符串P。</div>
<div>“2 x”，Alice询问Bob，集合T中有多少个字符串包含串S_x。（我们称串A包含串B，当且仅当B是A的子串）</div>
<div>Bob遇到了困难，需要你的帮助。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行，一个数n；</div>
<div>接下来n行，每行一个字符串表示S_i；</div>
<div>下一行，一个数q；</div>
<div>接下来q行，每行一个操作，格式见题目描述。</div>
<p></p></div>

# Output

<div class="content"><div>
<div>对于每一个Alice的询问，帮Bob输出答案。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
a<br/>
bc<br/>
abc<br/>
5<br/>
1 abca<br/>
2 1<br/>
1 bca<br/>
2 2<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
1</span></div>

# Hint

<div class="content"><p></p><div>【数据范围】</div><br/>
<div>1 &lt;= n,q &lt;= 100000；</div><br/>
<div>Alice和Bob拥有的字符串长度之和各自都不会超过 2000000；</div><br/>
<div>字符串都由小写英文字母组成。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 Dzy">鸣谢 Dzy</a></p></div>

