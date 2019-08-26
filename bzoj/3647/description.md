
# Description

<div class="content"><p><span style="font-size: medium">  某年某月某日，T64打开了某个无聊的密码网站。<br/>
  作为一个热衷于破译密码的SB，T64的IQ是非常高的，但是，一个人是无法在<br/>
一瞬间完成无数份密码的破译工作的（也许两瞬间），所以这个任务就交给你和<br/>
他共同来完成。<br/>
  一个密码对应一个字符串（仅包含小写英文字母），令这个串为S。你成功地<br/>
破解了这个密码串，当且仅当你找到了一个最短的T，使得S=T^K，即T重复K次。<br/>
密码S的关键值即为T的长度。<br/>
  这个网站的密码有一个特性，它是一个很长很长的母密码的一段，碰巧的是，你无意当中窃取到了这个密码串。作为一台十分负责的计算机，请帮助T64解<br/>
决这个问题。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">m+3行。第一行为正整数n，第二行为一个长为n的字符串s。第三行为一个正整数m，表示密码串的个数。第四至m+3行每行两个正整数L，R(L≤R)，表示询问的密码串在母密码串中的位置。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">共m行。每一行一个正整数，表示对应密码串的关键值。<br/>
</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
aababa<br/>
3<br/>
1  3<br/>
1  2<br/>
2  6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1   <br/>
5<br/>
<br/>
   </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"> 20  x≤ 500000,y≤ 2000000  <br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

