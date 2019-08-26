
# Description

<div class="content"><div><span style="font-size: medium">    约翰想要计算他那N(1≤N≤1000)只奶牛的名字的能量．每只奶牛的名字由不超过1000个字待构成，没有一个名字是空字体串，  约翰有一张“能量字符串表”，上面有M(1≤M≤100)个代表能量的字符串．每个字符串由不超过30个字体构成，同样不存在空字符串．一个奶牛的名字蕴含多少个能量字符串，这个名字就有多少能量．所谓“蕴含”，是指某个能量字符串的所有字符都在名字串中按顺序出现（不一定一个紧接着一个）．</span></div>
<div><span style="font-size: medium">    所有的大写字母和小写字母都是等价的．比如，在贝茜的名字“Bessie”里，蕴含有“Be”</span></div>
<div><span style="font-size: medium">“sI”“EE”以及“Es”等等字符串，但不蕴含“lS”或“eB”．请帮约翰计算他的奶牛的名字的能量．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入两个整数N和M，之后N行每行输入一个奶牛的名字，之后M行每行输入一个能量字符串．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    一共N行，每行一个整数，依次表示一个名字的能量．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
Bessie<br/>
Jonathan<br/>
Montgomery<br/>
Alicia<br/>
Angola<br/>
se<br/>
nGo<br/>
Ont<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 5 cows, and their names are &#34;Bessie&#34;, &#34;Jonathan&#34;,<br/>
&#34;Montgomery&#34;, &#34;Alicia&#34;, and &#34;Angola&#34;. The 3 good strings are &#34;se&#34;,<br/>
&#34;nGo&#34;, and &#34;Ont&#34;.<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
2<br/>
0<br/>
1<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
&#34;Bessie&#34; contains &#34;se&#34;, &#34;Jonathan&#34; contains &#34;Ont&#34;, &#34;Montgomery&#34; contains<br/>
both &#34;nGo&#34; and &#34;Ont&#34;, Alicia contains none of the good strings, and<br/>
&#34;Angola&#34; contains &#34;nGo&#34;.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

