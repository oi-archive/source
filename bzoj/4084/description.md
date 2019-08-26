
# Description

<div class="content"><div>
<div>给定两个字符串集合 S 和 T 。其中 S 中的所有字符串长度都恰好为 N ，而 T 中所有字符串长度都恰好为 M 。</div>
<div>且 N+M 恰好为偶数。如果记 S 中字符串全体为 S1，S2，...，STotalS ,而 T 中字符串全体为 T1，T2，...，TT</div>
<div>otalT 。现在希望知道有多少对 &lt;i,j&gt; ，满足将 Si 和 Tj 拼接后得到的字符串 Si+Tj 满足双旋转性。一个长度</div>
<div>为偶数字符串 W 可以表示成两段长度相同的字符串的拼接，即 W=U+V。如果 V 可以通过 U 旋转得到，则称 W 是</div>
<div>满足双旋转性的。比如说字符串 U=“vijos”可以通过旋转得到“ijosv”，“josvi”，“osvij” 或“svijo”</div>
<div>。那么“vijosjosvi”就是满足双旋转性的字符串。</div>
</div>
<div></div>
<p></p>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行输入四个正整数，分别为 TotalS，TotalT，N 和 M，依次表示集合 S 的大小，集合 T 的大小，集合 S 中字符串的长度和集合 T 中字符串的长度。</div>
<div>之后 TotalS 行，依次给出 S 中所有的字符串 Si，1≤i≤TotalS。保证每一个字符串长度都恰为 N ，且字符串只由 26 个小写字母组成。</div>
<div>之后 TotalT 行，依次给出 T 中所有的字符串 Ti，1≤i≤TotalT。保证每一个字符串长度都恰为 M ，且字符串只由 26 个小写字母组成。</div>
<div>2≤N*TotalS+M*TotalT≤4×10^6，N&gt;=M</div>
</div>
<div style="font-size: 11.8181819915771px;"></div>
<p></p></div>

# Output

<div class="content"><p>输出一个整数，表示满足要求的数字对 &lt;i,j&gt; 有多少个。</p>
<div style="font-size: 11.8181819915771px;"></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 7 3 <br/>
vijosvi <br/>
josvivi <br/>
vijosos <br/>
ijosvsv <br/>
jos <br/>
vij <br/>
ijo <br/>
jos</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

