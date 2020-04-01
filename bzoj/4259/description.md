
# Description

<div class="content"><div>很久很久以前，在你刚刚学习字符串匹配的时候，有两个仅包含小写字母的字符串A和B，其中A串长度为m，B串长度为n。可当你现在再次碰到这两个串时，这两个串已经老化了，每个串都有不同程度的残缺。</div>
<div>你想对这两个串重新进行匹配，其中A为模板串，那么现在问题来了，请回答，对于B的每一个位置i，从这个位置开始连续m个字符形成的子串是否可能与A串完全匹配?</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数m,n(1&lt;=m&lt;=n&lt;=300000)，分别表示A串和B串的长度。</div>
<div>第二行为一个长度为m的字符串A。</div>
<div>第三行为一个长度为n的字符串B。</div>
<div>两个串均仅由小写字母和*号组成，其中*号表示相应位置已经残缺。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行包含一个整数k，表示B串中可以完全匹配A串的位置个数。</div>
<div>若k&gt;0，则第二行输出k个正整数，从小到大依次输出每个可以匹配的开头位置（下标从1开始）。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 7<br/>
a*b<br/>
aebr*ob</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

