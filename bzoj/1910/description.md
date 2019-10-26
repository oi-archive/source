
# Description

<div class="content">IOI2002的颁奖典礼将在YONG-IN Hall隆重举行。人们在经历了充满梦幻的世界杯之后变得更加富于情趣。为了使颁奖典礼更具魅力，有人建议在YONG-IN Hall中搭建一个I字型的颁奖台，以此代表信息学Informatics。考虑到比赛的赞助商们可能要在YONG-IN Hall中摆设了许多展示台，他们可能不愿意移动展示台的位置。你作为IOI2002的金牌得主自然地成为了他们求助的对象。
YONG-IN Hall是一个矩形的网格区域。每个赞助商的展示台都占据了若干个单位网格。I型颁奖台将正向搭建，且平行于YONG-IN Hall的边缘。I型颁奖台是由三个矩形相接叠成的，其中上方和下方的矩形的两侧必须都超出中间的矩形，否则将被误解成T, L, J等字母。例如：
<img border="0" src="/source/bzoj/1910/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MTBfMS5qcGc=.jpg"/> 
这是两个合法的I型颁奖台，而以下三种情况均不合法：
<img border="0" src="/source/bzoj/1910/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MTBfMi5qcGc=.jpg"/> 
希望你编程寻找面积最大的I型颁奖台，使其不覆盖任何展示台。
</div>

# Input

<div class="content">第一行包含两个正整数n, m(1&lt;=n,m&lt;=200)，分别表示YONG-IN Hall的矩形网格区域的行数和列数。以下n行每行包含m个数字，非0即1，每个数字描述一个单位网格，1表示该单位网格存在展示台，0表示该单位网格不存在展示台。
</div>

# Output

<div class="content">仅包含一个正整数，表示最大的I型颁奖台的面积。如果不存在合法的I型颁奖台，则输出0。
</div>

# Sample Input

<div class="content"><span class="sampledata">6 8<br/>
1 1 1 1 1 0 0 1<br/>
1 0 0 0 0 1 1 1<br/>
1 0 0 0 0 0 1 1<br/>
1 0 1 0 1 0 1 0<br/>
1 0 0 0 0 0 0 1<br/>
1 1 0 0 0 1 0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
</span></div>

# Hint

<div class="content"><p><img border="0" src="/source/bzoj/1910/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MTBfMy5qcGc=.jpg"/> </p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

