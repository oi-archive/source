
# Description

<div class="content"><div>Just like humans, cows often appreciate feeling they are unique in some way. Since Farmer John&#39;s cow</div>
<div>s all come from the same breed and look quite similar, they want to measure uniqueness in their name</div>
<div>s.Each cow&#39;s name has some number of substrings. For example, &#34;amy&#34; has substrings {a, m, y, am, my,</div>
<div> amy}, and &#34;tommy&#34; would have the following substrings: {t, o, m, y, to, om, mm, my, tom, omm, mmy, </div>
<div>tomm, ommy, tommy}.A cow name has a &#34;uniqueness factor&#34; which is the number of substrings of that na</div>
<div>me not shared with any other cow. For example, If amy was in a herd by herself, her uniqueness facto</div>
<div>r would be 6. If tommy was in a herd by himself, his uniqueness factor would be 14. If they were in </div>
<div>a herd together, however, amy&#39;s uniqueness factor would be 3 and tommy&#39;s would be 11.Given a herd of</div>
<div>cows, please determine each cow&#39;s uniqueness factor.</div>
<div>
<div>定义一个字符串的「独特值」为只属于该字符串的本质不同的非空子串的个数。如 &#34;amy&#34; 与 “tommy” 两个串，</div>
<div>只属于 &#34;amy&#34; 的本质不同的子串为 &#34;a&#34; &#34;am&#34; &#34;amy&#34; 共 3 个。只属于 &#34;tommy&#34; 的本质不同的子串为 &#34;t&#34; &#34;to&#34; &#34;</div>
<div>tom&#34; &#34;tomm&#34; &#34;tommy&#34; &#34;o&#34; &#34;om&#34; &#34;omm&#34; &#34;ommy&#34; &#34;mm&#34; &#34;mmy&#34; 共 11 个。 所以 &#34;amy&#34; 的「独特值」为 3 ，&#34;tommy</div>
<div>&#34; 的「独特值」为 11 。给定 N 个字符集为小写英文字母的字符串，所有字符串的长度和小于 10^5 ，求出每个</div>
<div>字符串「独特值」</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input will contain NN (1≤N≤10^5). </div>
<div>The following NN lines will each contain the name of a cow in the herd. </div>
<div>Each name will contain only lowercase characters a-z. </div>
<div>The total length of all names will not exceed 10^5</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Output NN numbers, one per line, describing the uniqueness factor of each cow.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
amy<br/>
tommy<br/>
bessie</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
11<br/>
19</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum 鸣谢infinityedge提供译文">Platinum 鸣谢infinityedge提供译文</a></p></div>

