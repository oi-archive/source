
# Description

<div class="content"><p> JYY最近迷上了拼图游戏。作为一个计算机科学家，JYY有一套黑白色的拼图，他希望通过合理的拼接，使得拼出的最终图案中，能包含面积最大的全白色子矩形。JYY一共有S块拼图，并且由1到S编号。编号为i的拼图是一个N行列的方格矩形，每个方格都为黑色或者白色。一开始JYY将他的这S块拼图按照编号顺序左右相连依次放在桌上拼成了一个N行M列（这里M=Sigma(Wi)(1&lt;=i&lt;=S）的大矩形。之后JYY发现，可以通过改变这S块拼图的连接次序，使得拼成的N行M列的大矩形中，最大全白子矩形面积变大。现在JYY想知道，怎么拼才能得到最大的全白子矩形呢？请你帮助他计算出最佳的拼接方案。</p></div>

# Input

<div class="content"><p>每个输入文件中包含多组测试数据。输入文件第一行包含一个整数T，代表</p>
<div>测试数据的组数，接下来按顺序描述了每组测试数据。</div>
<div>每组测试数据的第一行包含两个整数S和N。</div>
<div>接下来S组输入，第i组对应编号为i的拼图。</div>
<div>在第i组输入中，第一行包含一个整数；</div>
<div>接下来N行描述一个N行列的0/1矩形；</div>
<div>其中第x行y列为0则表示该拼图对应位置的颜色是白色，反之则为黑色。</div>
<div></div>
<p></p>
<div></div></div>

# Output

<div class="content"><p> 对于每组数据输出一行包含一个整数ans，表示最大可能的全白色子矩形的面积。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
34<br/>
4<br/>
1001<br/>
0000<br/>
0010<br/>
1001<br/>
3<br/>
000<br/>
010<br/>
000<br/>
011<br/>
2<br/>
00<br/>
10<br/>
01<br/>
00</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据满足1&lt;=S,N,Wi&lt;=10^5,N*Sigma(Wi)&lt;=10^5,T&lt;=3</div><br/>
<div>添加数组一组--2015.02.28</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round2 By 佚名上传">Round2 By 佚名上传</a></p></div>

