
# Description

<div class="content"><div>SD有一名神犇叫做Oxer，他觉得字符串的题目都太水了，于是便出了一道题来虐蒟蒻yts1999。</div>
<div></div>
<div>他给出了一个字符串T，字符串T中有且仅有4种字符 &#39;A&#39;, &#39;B&#39;, &#39;C&#39;, &#39;D&#39;。现在他要求蒟蒻yts1999构造一个新的字符串S，构造的方法是：进行多次操作，每一次操作选择T的一个子串，将其加入S的末尾。</div>
<div></div>
<div>对于一个可构造出的字符串S，可能有多种构造方案，Oxer定义构造字符串S所需的操作次数为所有构造方案中操作次数的最小值。</div>
<div></div>
<div>Oxer想知道对于给定的正整数N和字符串T，他所能构造出的所有长度为N的字符串S中，构造所需的操作次数最大的字符串的操作次数。</div>
<div></div>
<div>蒟蒻yts1999当然不会做了，于是向你求助。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数N，表示要构造的字符串长度。</div>
<div>
<div></div>
<div>第二行包含一个字符串T，T的意义如题所述。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出文件包含一行，一个整数，为你所求出的最大的操作次数。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
ABCCAD</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><div>【样例说明】</div><br/>
<div></div><br/>
<div>例如字符串&#34;AAAAA&#34;，该字符串所需操作次数为5，不存在能用T的子串构造出的，且所需操作次数比5大的字符串。</div><br/>
<div></div><br/>
<div>【数据规模和约定】</div><br/>
<div>对于100%的数据，1 ≤ N ≤ 10^18，1 ≤ |T| ≤ 10^5。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By yts1999">By yts1999</a></p></div>

