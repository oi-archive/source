
# Description

<div class="content"><div>一个串T是S的循环节，当且仅当存在正整数k，使得S是T^k(即T重复k次)的前缀，比如abcd是abcdabcdab的循环节</div>
<div>。给定一个长度为n的仅由小写字符构成的字符串S，请对于每个k(1&lt;=k&lt;=n)，求出S长度为k的前缀的最短循环节的</div>
<div>长度per_i。字符串大师小Q觉得这个问题过于简单，于是花了一分钟将其AC了，他想检验你是否也是字符串大师。</div>
<div>小Q告诉你n以及per_1,per_2,...,per_n，请找到一个长度为n的小写字符串S，使得S能对应上per。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=100000)，表示字符串的长度。</div>
<div>第二行包含n个正整数per_1,per_2,...per_n(1&lt;=per_i&lt;=i)，表示每个前缀的最短循环节长度。</div>
<div>输入数据保证至少存在一组可行解。</div></div>

# Output

<div class="content"><div>输出一行一个长度为n的小写字符串S，即某个满足条件的S。</div>
<div>若有多个可行的S，输出字典序最小的那一个。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 2 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">ababb<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

