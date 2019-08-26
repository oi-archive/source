
# Description

<div class="content"><div>小Z最近迷上了拼图游戏，然而智商有限，他总是无法拼出完整图案。游戏是这样的：首先小Z会得到一些拼图碎片</div>
<div>，然后他试着重新排列这些碎片使得它们组成一个大小为4*4的正方形。如下图。注意小Z不能旋转或者翻转这些碎</div>
<div>片。</div>
<div><img src="source/bzoj/5156/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xMS5qcGc=.jpg" width="273" height="272" alt=""/></div>
<div>小Z得到如图1的碎片，然后经过重新排列得到图2的正方形。由于小Z实在太笨了，聪明的你请写一个程序帮助他来</div>
<div>解决这个问题吧。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组数据，请使用EOF。</div>
<div>每组数据的的第一行包含一个正整数N，表示碎片的个数。</div>
<div>接下来输入N个碎片。每个碎片的第一行是两个正整数r和c，表示这个碎片的行数和列数。</div>
<div>接下来是r行，每一行包含c个字符’0’或’1’</div>
<div>’1’表示碎片占据这个位置，’0’表示该位置为空。</div>
<div>数据保证每个碎片都是完整的一片(即’1’是相互连通的)，并且没有行或者列全部为’0’。</div>
<div>N&lt;=16</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>如果无法组成一个正方形，输出”No solution”；</div>
<div>如果有多组解，输出”Yes,many!”。否则，输出”Yes, only one!”</div>
<div>接下来输出一个 4 * 4 的矩阵 H，Hij表示位置 i, j 的碎片编号。碎片编号从 1 开始</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 3<br/>
111<br/>
101<br/>
4 2<br/>
01<br/>
01<br/>
11<br/>
01<br/>
2 1<br/>
1<br/>
1<br/>
3 2<br/>
10<br/>
10<br/>
11<br/>
4<br/>
1 4<br/>
1111<br/>
1 4<br/>
1111<br/>
1 4<br/>
1111<br/>
1 4<br/>
1111</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes, only one!<br/>
1112<br/>
1412<br/>
3422<br/>
3442<br/>
Yes, many!</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

