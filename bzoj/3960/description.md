
# Description

<div class="content"><div>为了了解早期文明，考古学家们经常会研究古代语言的书籍。有这样一种语言，它在3000多年前古老的埃及曾经被使用，是一种基于象形符号的语言。图1表示了六种象形符号以及它们的名字。在这个问题中，你需要写一个程序去辨识这6个字符。</div>
<div><img src="source/bzoj/3960/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC8zMy5qcGc=.jpg" width="819" height="282" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入包括多组测试用例，每一组都描述了一个图像，这个图像包含一或多个从图1中选出的象形符号。这些图像以这样的方式给出：一系列黑色像素(用1表示)和白色像素(用0表示)组成的扫描线。在输入数据中，每个扫描线都是用十六进制的方法进行编码的。例如，八个像素的序列10011100(一个黑色像素，后面跟着两个白色像素，等等)可以表示为十六进制数字9c。在十六进制中，只会出现数字和小写字母a至f。每个测试用例的第一行包含两个整数，H和W：H(0&lt;H≤200)是图像中扫描线的个数，W(0&lt;W≤50)是每一行十六进制的字符数。接下来的H行从上到下给出了十六进制编码扫描线。输入的图像遵循以下规则：</div>
<div>1. 图像仅包含图1所示的象形文字。</div>
<div>2. 每个图像至少有一个有效的象形文字。</div>
<div>3. 每个黑色像素都是一个有效象形文字的一部分。</div>
<div>4. 每个象形文字由一个联通的黑色像素块组成，对于每个黑色像素，至少在其上下左右至少有一块黑色像素块。</div>
<div>5. 象形文字互不接触，而且不存在一个象形文字在另一个的内部。</div>
<div>6. 如果有两块黑色像素对角线相接处，则必然存在一块公共接触的黑色像素。</div>
<div>7. 象形文字可能会扭曲，但是它的拓扑结构必然会和图1中所示的一个等价。(如果一个图像可以通过拉伸但不被毁坏的方式转化成另一个，则它们是拓扑等价的)</div>
<div>最后一组测试用例后紧跟一行，包含两个0，表示输入结束。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试用例，先输出它的编号，后面跟着一个字符串，表示每一个出现在图像中的象形文字，使用下面的编码：</div>
<div>
<div>Ankh: A</div>
<div>Wedjat: J</div>
<div>Djed: D</div>
<div>Scarab: S</div>
<div>Was: W</div>
<div>Akhet: K</div>
<div>对于每个输出的字符串，字符要按照字典序输出。请参照输出样例的格式。</div>
<div>输入样例包含图2和图3所示的测试点。由于空间的限制，样例数据并没有显示完全。</div>
<div><img src="source/bzoj/3960/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC80NC5qcGc=.jpg" width="165" height="201" alt=""/></div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">100 25<br/>
0000000000000000000000000<br/>
0000000000000000000000000<br/>
...(省略50行)...<br/>
00001fe0000000000007c0000<br/>
00003fe0000000000007c0000<br/>
...(省略44行)...<br/>
0000000000000000000000000<br/>
0000000000000000000000000<br/>
150 38<br/>
00000000000000000000000000000000000000<br/>
00000000000000000000000000000000000000<br/>
...(省略75行)...<br/>
0000000003fffffffffffffffff00000000000<br/>
0000000003fffffffffffffffff00000000000<br/>
...(省略69行)...<br/>
00000000000000000000000000000000000000<br/>
00000000000000000000000000000000000000<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: AKW<br/>
Case 2: AAAAA</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据 0＜H≤200 0＜W≤50</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

