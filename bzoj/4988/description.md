
# Description

<div class="content"><div>有一个塔，他的名字叫做粽粑，粽粑的每一层都有一个颜色c．</div>
<div>粽粑非常厉害，它在吸收天地精华之后会长高，粽粑的长高方式有两种：</div>
<div>1．在塔顶长出一层．</div>
<div>2．在塔底长出一层，即原来的第一层变成第二层，第二层变成第三层，以此类推，新长出来的是第一层，</div>
<div>粽粑有可能在某个时刻不是很开心，这个时候它会撤销它的前若干次长高，</div>
<div>你现在想知道粽粑长高的奥秘，于是找到了粽粑，发现它的入口上写着这么一句话：</div>
<div>要进入粽粑，请找出一段最长的塔的区间，满足翻转后颜色不变，</div>
<div>粽粑会不断的长高（或撤销），所以它每次长高后你都要回答，</div>
<div>为了你的方便，粽粑一开始的高度为0．</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数q，表示粽粑的操作个数，</div>
<div>第二行一个字符串s[O..q*3-1]</div>
<div>对于下标为3*k的字符ch：</div>
<div>ch=&#39;1&#39;表示第k+l次操作是在塔顶长出一层．</div>
<div>ch=&#39;2&#39;表示第尼+1次操作是在塔底长出一层．</div>
<div>c允=&#39;3&#39;表示第k+l次操作是撤回，</div>
<div>对于第K次操作，不妨设s[3k-2，3k-1]那么组成的两位数是Num，设第k-1次操作的答案是lans.</div>
<div>如果该操作是长高操作，这次操作的颜色是(num+lans) mod 100．否则连续撤回的次数是(num+lans)mod 100.</div>
<div>Q≤10^7.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行一个数，表示所有q次操作后的答案的和，</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
101102100299199198298</span></div>

# Sample Output

<div class="content"><span class="sampledata">25<br/>
Hint<br/>
加密前的数据是：<br/>
7<br/>
101103101202102103203<br/>
对应的字符串是abacaba</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

