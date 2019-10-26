
# Description

<div class="content"><img border="0" src="/source/bzoj/1918/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MTguanBn.jpg"/> </div>

# Input

<div class="content">第一行包括一个整数 n，表示每队的选手数。 
第二行到第n + 1 行每行包含n 个实数，整体为一个� × �的矩阵，表示A 队
对B 队的胜率。其中第 i + 1 行的第 j个数表示选手 Ai对选手Bj时的胜率。 
第n+2 行为空行。 
第n + 3 行到第2n + 2 行每行包含n 个实数，同样为一个� × �的矩阵，表示
A队对C 队的胜率。其中第i + n + 2 行的第 j个数表示选手Ai对选手 Cj时的胜
率。 
第2n + 3 行为空行。 
第2n + 4 行到第3n + 3 行每行包含n 个实数，整体为一个� × �的矩阵，表
示B 队对 C队的胜率。其中第i + 2n + 3 行的第 j个数表示选手 Bi对选手Cj时的
胜率。 </div>

# Output

<div class="content">仅包含一个实数，保留 6 位小数，表示 A 队获得冠军的概
率。 </div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
1.0 0.0 0.5 <br/>
0.5 1.0 1.0 <br/>
0.5 0.5 0.5 <br/>
<br/>
0.5 0.5 1.0 <br/>
0.5 0.0 0.5 <br/>
0.5 0.5 0.5 <br/>
 <br/>
0.5 0.0 1.0 <br/>
0.5 0.5 0.5 <br/>
0.5 0.5 0.5  </span></div>

# Sample Output

<div class="content"><span class="sampledata">0.273438 <br/>
</span></div>

# Hint

<div class="content"><p><br/>
30%的数据中，n ≤ 4。 <br/>
40%的数据中，n ≤ 5。 <br/>
100%的数据中，n ≤ 7。 <br/>
对于10%的数据有三个胜率矩阵中，每个矩阵的元素都相同，但不同矩阵的<br/>
数字可能不同。 <br/>
 </p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

