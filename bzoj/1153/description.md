
# Description

<div class="content"><div>5岁的小P对剪纸很感兴趣，他总是喜欢把一个矩形的纸片剪成一个又一个的凸多边形。但是，每一次剪完后，他总</div>
<div>是怀疑自己弄丢了一些纸片。聪明的他想到了一个方法来检测纸片是否弄丢：他将这些凸多边形拼起来，如果能够</div>
<div>拼成一个矩形，他就认为纸片没有弄丢。由于纸片的数量不是很多，这个工作并不难。但是，久而久之，他对这项</div>
<div>工作不感兴趣了，所以，他找到了你，希望你能够告诉他，这些凸多边形纸片能不能够拼成矩形。</div></div>

# Input

<div class="content"><div>第一行只有一个正整数n（1≤n≤8），表示凸多边形的个数。</div>
<div>以下n行每一行描述一个凸多边形，</div>
<div>格式如下：第i+1行的第一个数mi（3≤mi≤8）表示凸多边形的点数，</div>
<div>接下来有mi对实数，一对实数给出了一个点的坐标，</div>
<div>这mi个顶点按照从任意一个顶点出发的逆时针顺序给出。</div>
<div>且所有实数都在(-1000,1000)的范围内，小数点后不超过8位。</div></div>

# Output

<div class="content"><div>如果不能拼成矩形，输出只有一行“No”。</div>
<div>如果能拼成矩形，输出的第一行为“Yes”。接下来的n行描述拼法。</div>
<div>如果能够拼成一个X*Y的矩形，那么矩形的四个顶点的坐标是(0,0)、(0,Y)、(X,Y)、(X,0)。</div>
<div>这n行输出每一个凸多边形的顶点的坐标（拼成矩形后）。</div>
<div>按照输入的顺序，即第一个输出的凸多边形对应输入的第一个凸多边形。</div>
<div>对于每一个凸多边形，输出也按照输入的顺序，即一个多边形的第一个顶点对应输入的第一个顶点。</div>
<div>这样，输出总共有n行，第i行有mi对数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
4 0 0 4 -1 5 4 0 4<br/>
4 0 0 5 -1 8 3 0 3<br/>
4 0 0 0 -8 3 -4 4 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
0 4 4 3 5 8 0 8<br/>
5 8 4 3 8 0 8 8<br/>
0 0 8 0 4 3 0 4</span></div>

# Hint

<div class="content"><p></p><p><img alt="" border="0" src="/source/bzoj/1153/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNTMuanBn.jpg"/> </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

