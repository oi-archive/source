
# Description

<div class="content"><div>有三个字符串集合， Pre 、 Mid 和 Suf 。我们称一个字符串的二元组 (p, q) 合法，当且仅当：</div>
<div>1. p 属于集合 Pre ；</div>
<div>2. q 属于集合 Suf ；</div>
<div>3. 存在 p 的一个长度不小于 k1 的子串 p&#39;、 q 的一个长度不小于 k2 的子串 q&#39; ，以及集合 Mid 中的一个字符串 s ，使得 p&#39; + q&#39; 是 s 的一个子串。这里的 + 代表字符串的连接。</div>
<div>你可以进行任意次操作，一次操作中，你需要选择一个合法的二元组 (p, q) ，并从集合 Pre 中删去字符串 p ，从集合 Suf 中删去字符串 q 。求最多的操作次数。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含三个正整数 s1 、 s2 和 s3 ，分别代表集合 Pre 、 Mid 和 Suf 中字符串的个数。</div>
<div>第二行包含两个正整数 k1 和 k2 ，含义如问题描述中所述。</div>
<div>接下来 s1 行，每行包含一个字符串，代表集合 Pre 中的一个字符串。</div>
<div>接下来 s2 行，每行包含一个字符串，代表集合 Mid 中的一个字符串。</div>
<div>接下来 s3 行，每行包含一个字符串，代表集合 Suf 中的一个字符串。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行，包含一个正整数，表示最多可以操作的次数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 4<br/>
2 3<br/>
aab<br/>
bbb<br/>
aabbcdd<br/>
cdd<br/>
bcd<br/>
zz<br/>
bcde</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><div>样例中合法的二元组有 (aab, bcd) 、 (aab, bcde) 和 (bbb, ccd) 。</div><br/>
<div>字符串 zz 的长度小于 k2 ，因此不存在包含这个字符串的合法二元组。</div><br/>
<div>数据规模和约定</div><br/>
<div>令 len(S) 为集合 S 中所有字符串的长度和。再令 L = max{len(Pre), len(Mid), len(Suf)} 。</div><br/>
<div>对于 10% 的数据， s1, s2, s3 ≤ 5 ， L ≤ 30 。</div><br/>
<div>对于 20% 的数据， s1, s2, s3 ≤ 30 ， L ≤ 300 。</div><br/>
<div>对于 50% 的数据， s1, s2, s3 ≤ 500 ， L ≤ 10000 。</div><br/>
<div>对于 100% 的数据， s1, s2, s3 ≤ 25000 ， L ≤ 50000 ， 0 ≤ k1, k2 ≤ L 。字符串只含有小写英文字母。</div><br/>
<div>注意题目中的“集合”和数学中定义的集合不同，其中可以有相同的字符串。</div><br/>
<div>尚无数据，请不要提交！求此题数据！</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测">2014年国家集训队十五人互测</a></p></div>

