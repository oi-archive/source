
# Description

<div class="content"><div>1-quotation指一个以单引号开头并以另一个单引号结尾，而且中间没有单引号的字符串。例如&#39;this is a string</div>
<div>&#39;是一个1-quotation。对于k＞1，k-quotation以k个单引号开头，以另外k个单引号结尾，并且中间嵌套了一个字</div>
<div>符串。嵌套在其中的字符串是一系列(k-1)-quotation，它们可能紧接前面，分开，或者跟在若干非引号字符后面</div>
<div>。例如&#39;&#39;All &#39;work&#39; and no &#39;play&#39;&#39;&#39;是一个2-quotation。给出一个字符串的描述，请计算它最大可能的嵌套级</div>
<div>（即最大的k使该字符串是一个k-quotation）。</div></div>

# Input

<div class="content"><div>输入两行，第一行一个数n（1≤n≤100）。</div>
<div>第二行n个数a1到an（2≤ai≤100），描述一个字符串：这个字符串以a1个单引号开始，</div>
<div>接下来是正整数个非引号字符，然后是a2个单引号，以此类推，最后以an个单引号结束。</div></div>

# Output

<div class="content"><div>输出最大的k使得输入描述的串是一个k-quotation。如果没有这样的k，输出no quotation。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
81<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">no quotation<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="color: rgb(255, 0, 0);"> 注意Ai&gt;=1</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Shimakaze提供译文">鸣谢Shimakaze提供译文</a></p></div>

