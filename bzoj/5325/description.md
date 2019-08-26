
# Description

<div class="content"><div>JSOI 王国的码农JYY 最近沉迷氪金手游无法自拔，于是他想尽可能快地完成上司交付的编码工作才能有更多的时间肝手游。</div>
<div>JYY 在用光速读完代码要求之后，以常人难以想象的速度先在脑海中构造出了对应的代码，接下来的问题就只有录入了。</div>
<div>JYY 想输入的程序可以表示为由数字0到9组成的一个字符串。他有两种输入方式：</div>
<div>第一种输入方式是在字符串末尾直接输入某个字符。但由于沉迷氪金，JYY只能买得起很糟糕的键盘，用这个键盘输入数字i需要ci时间。</div>
<div>第二种输入方式是复制粘贴，JYY 可以先选中已经输入内容的某个子串再将其粘贴到目前串的末尾。但由于沉迷氪金，JYY 的鼠标也很糟糕，</div>
<div>每多选中一个字符他就需要花tc时间，并且需要额外tp时间来完成粘贴操作。</div>
<div>所以复制一段长度为 l 的子串并粘贴到末尾所需要的时间是tc * l + tp。粘贴完成后被选中的子串将不再被选中</div>
<div>（下次复制粘贴操作即便粘贴同一子串，仍需重新选中）。</div>
<div>现在JYY 想知道只使用这两种操作最短要花多长时间才能输入他想输入的程序。</div>
<div></div></div>

# Input

<div class="content"><div>输入第一行一个字符串S表示JYY 想要输入的程序。</div>
<div>输入第二行十个正整数分别表示c0到c9，表示直接录入一个字符需要的时间。</div>
<div>输入第三行两个正整数tc和tp表示复制粘贴需要的时间。</div>
<div>|S| ≤ 10^5, 1 ≤ ci ≤ 10^3, 1 ≤ tc, tp ≤ 10^4。</div>
<div></div></div>

# Output

<div class="content"><div>输入一个正整数，表示所需要的最少总时间。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">0123<br/>
1 2 3 4 5 6 7 8 9 10<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

