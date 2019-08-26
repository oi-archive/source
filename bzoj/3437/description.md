
# Description

<div class="content"><p><span style="font-size: medium;">小P在MC里有n个牧场，自西向东呈一字形排列（自西向东用1…n编号），于是他就烦恼了：为了控制这n个牧场，他需要在某些牧场上面建立控制站，每个牧场上只能建立一个控制站，每个控制站控制的牧场是它所在的牧场一直到它西边第一个控制站的所有牧场（它西边第一个控制站所在的牧场不被控制）（如果它西边不存在控制站，那么它控制西边所有的牧场），每个牧场被控制都需要一定的花费（毕竟在控制站到牧场间修建道路是需要资源的嘛~），而且该花费等于它到控制它的控制站之间的牧场数目（不包括自身，但包括控制站所在牧场）乘上该牧场的放养量，在第i个牧场建立控制站的花费是ai，每个牧场i的放养量是bi，理所当然，小P需要总花费最小，但是小P的智商有点不够用了，所以这个最小总花费就由你来算出啦。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个整数 n 表示牧场数目</span></p>
<p><span style="font-size: medium">第二行包括n个整数，第i个整数表示ai</span></p>
<p><span style="font-size: medium">第三行包括n个整数，第i个整数表示bi</span></p>
<p><span style="font-size: medium"> </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">只有一行，包括一个整数，表示最小花费</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2424<br/>
3142<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
 样例解释<br/>
选取牧场1，3，4建立控制站，最小费用为2+(2+1*1)+4=9。<br/>
1&lt;=n&lt;=1000000, 0 &lt; a i ,bi &lt; = 10000<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=KpmCup#0 By Greens">KpmCup#0 By Greens</a></p></div>

