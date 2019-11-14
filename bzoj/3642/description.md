
# Description

<div class="content"><div style="line-height: 12pt"><span style="font-size: medium">Leopold买了n块蛋糕, 这些蛋糕排成一排，从左到右记为1到n，第i块蛋糕最初的美味度为di。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">Leopold每次固定最先吃第k块蛋糕，于是位置k就空出来了。之后他吃的每一块蛋糕总是位于某个空的位置旁边，并且是美味度最低的一块。因此在任何时刻，所有空的位置是一段连续的区间。Leopold会装饰自己的蛋糕来增加它的美味度，被加过装饰的蛋糕一定会成为最美味的10个蛋糕之一，任何时候都不存在两块美味度相同的蛋糕。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">Leopold想知道在他吃到某块蛋糕b之前需要吃掉多少块蛋糕。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="line-height: 12pt"><span style="font-size: medium">第一行两个整数n和k，表示蛋糕的数量和Leopold吃的第一块蛋糕的位置。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">第二行n个不同的整数d1,d2...,dn，表示第i块蛋糕最初的美味度。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">第三行一个整数q，表示操作的数量。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">下面q行会包括以下两种操作。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">(1)E i e 蛋糕i被装饰成了第e美味的蛋糕（即原来前e-1美味的蛋糕不变，原来第e美味的蛋糕变成了第e+1美味的蛋糕，以此类推）注意每次装饰一定会增加美味度。</span></div>
<div style="line-height: 12pt"><span style="font-size: medium">(2)F b输出Leopold吃到蛋糕b之前需要吃掉多少块蛋糕。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="line-height: 12pt"><span style="font-size: medium">对于每个F操作，输出一行一个整数，表示蛋糕的数量。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
5 1 2 4 3<br/>
17<br/>
F 1<br/>
F 2<br/>
F 3<br/>
F 4<br/>
F 5<br/>
E 2 1<br/>
F 1<br/>
F 2<br/>
F 3<br/>
F 4<br/>
F 5<br/>
E 5 2<br/>
F 1<br/>
F 2<br/>
F 3<br/>
F 4<br/>
F 5<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1<br/>
0<br/>
2<br/>
3<br/>
4<br/>
3<br/>
0<br/>
1<br/>
2<br/>
4<br/>
3<br/>
0<br/>
1<br/>
2<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>在第一次装饰前，蛋糕会按顺序3,2,4,5,1被吃掉。但装饰以后，由于蛋糕2美味度较高，它不会很快被吃掉，而蛋糕4和5会先被吃掉。但是第二次对蛋糕5的装饰对于吃掉蛋糕的顺序没有影响。<br/><br/>
 <br/><br/>
对于100%的数据满足<br/><br/>
1≤k≤n≤250000<br/><br/>
1≤q≤500000<br/><br/>
1≤e≤10</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=uploaded by dwellings">uploaded by dwellings</a></p></div>

