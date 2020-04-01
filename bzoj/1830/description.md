
# Description

<div class="content"><p><span style="font-size: medium">小可可得到了一个可爱的Y型项链。小可可现在的项链是这个样子的：项链的最中间有一颗大珍珠作为结合点，从大珍珠上连出来3条由各种宝石串起来的链子。小可可希望让这3个链子完全一样，她每次可以从一端取下来一个宝石，或者从一端安上去一个宝石。假设小可可每种宝石都有无数多个，小可可希望用尽量少的操作次数得到想要的Y型项链。小可可对于所得到的Y型项链的宝石数没有特殊的要求，所以即使你把所有宝石都弄下来了，也是一个可以接受的方案（三根光秃秃的绳子也是完全一样的）。 换句话说，给你3个字符串，你每一次可以向一个字符串的末端删除一个字符或添加一个字符，你需要用尽量少的操作次数使得这3个字符串变成一样的。  </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">一共有3行，每行有一个数字N，表示Y型项链的这个链子有N个宝石，然后是一个空格，然后是N个&#39;A&#39;和&#39;Z&#39;之间的字符，表示这个链子上的宝石，每个字母表示一种不同的宝石，这个字符串最左边的字符表示的是离大珍珠最近的那个宝石，而最右边的表示的是在顶端的宝石。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">只有一个整数：小可可所需要的最少的操作次数。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 CAT<br/>
3 TAC<br/>
5 CATCH<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">提示：把TAC这3个珠子一个一个地拿下来，然后按顺序装入CAT，这样一共是6次操作。此外，你还需要把CH这两个宝石从CATCH上移走。因此一共是八次操作。 数据范围： 100%的数据中，N&lt;=50。 50%的数据中，N&lt;=20。 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

