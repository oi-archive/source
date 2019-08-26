
# Description

<div class="content"><div>
<div>在遥远的未来，行星之间的食品运输将依靠单向的贸易路线。每条路径直接连接两个行星，且其运输时间是已知的</div>
<div>。贸易商协会打算利用一项最近发现的新技术——超空间旅行，以增加一些新的航线。通过超空间旅行的航线也是</div>
<div>单向的。由于该项技术仍处于试验阶段，超空间旅行的时间目前是未知的，但它不取决于行星之间的距离，所以每</div>
<div>个超空间旅行的路线将花费等量的时间。下图是三个相互联通的行星及其运输时间的例子。行星使用正整数标号，</div>
<div>超空间旅行时间记为“x”（图片对应第输入样例）：过境的时间以天计，并且始终是一个正整数。贸易商协会希</div>
<div>望对引进新航线的后果进行分析：对于某两个行星A和B，他们想知道对于任意的x，从A到B的最短路径的总中转时</div>
<div>间的所有可能的值。例如，在上述情况中，从星球2到星球1的最短路径所需时间可以取值5（如果x≥5），4，3，2</div>
<div>，或1天（如果x&lt;5）</div>
</div>
<p class="MsoNormal" align="left" style="text-indent: 27pt; "><img src="source/bzoj/3482/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMy9hYS5qcGc=.jpg" width="339" height="186" alt=""/></p>
<p class="MsoNormal" align="left" style="text-indent: 27pt; "></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US"> </span></span></p>
<p class="MsoNormal" align="left" style="text-indent: 27pt; "></p></div>

# Input

<div class="content"><div>输入的第一行包含两个整数P和R，分别代表行星的数目和航线数量，1≤P≤500，0≤R≤10000。接下来的R条航线</div>
<div>路径包含两或三个整数：行星标号C和D（1≤C，D≤P，C≠D），和T，从C到D的旅行时间。对于传统的路径，T是一</div>
<div>个整数（1≤T≤1000000），超空间航线中，T是字符“x”。 可以存在多行有两个相同的行星。下面的行中包含的</div>
<div>整数Q（1≤Q≤10），表示查询的数量。以下Q行包含两个整数星球标号（A和B，A≠B），为贸易商协会的查询：“</div>
<div>从A到B的最短路径时间的可能值是什么？</div>
<div>
<p class="MsoNormal" align="left" style="text-indent: 27pt; "></p>
<p class="MsoNormal"></p>
</div>
<div></div></div>

# Output

<div class="content"><div>输出必须包含q行，每行??一个查询。每一行都必须包含两个整数：不同的可能值的数目和它们的总和。如果不同</div>
<div>的可能值的数目是无限的，该行只输出“inf”。如果没有从A到B的路径，不同的可能值的数目及它们的总和都是0</div>
<div>。</div>
<div>
<p class="MsoNormal" align="left" style="text-indent: 27pt; "></p>
<p class="MsoNormal"></p>
</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 x<br/>
2 3 x<br/>
3 4 x<br/>
1 4 8<br/>
3<br/>
2 1<br/>
1 3<br/>
1 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 0<br/>
inf<br/>
3 17</span></div>

# Hint

<div class="content"><p></p><p> 2016.6.15新加数据一组，未重测</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Hta">By Hta</a></p></div>

