
# Description

<div class="content"><p><span style="font-size: medium">婷婷是个喜欢矩阵的小朋友,有一天她想用电脑生成一个巨大的n行m列的矩阵(你不用担心她如何存储)。她生成的这个矩阵满足一个神奇的性质：若用F[i][j]来表示矩阵中第i行第j列的元素，则F[i][j]满足下面的递推式:<br/>
<br/>
F[1][1]=1<br/>
F[i,j]=a*F[i][j-1]+b (j!=1)<br/>
F[i,1]=c*F[i-1][m]+d (i!=1)<br/>
递推式中a,b,c,d都是给定的常数。<br/>
<br/>
现在婷婷想知道F[n][m]的值是多少,请你帮助她。由于最终结果可能很大，你只需要输出F[n][m]除以1,000,000,007的余数。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">一行有六个整数n,m,a,b,c,d。意义如题所述</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">包含一个整数，表示F[n][m]除以1,000,000,007的余数</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 1 3 2 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">85</span></div>

# Hint

<div class="content"><p></p><p>样例中的矩阵为：<br/><br/>
1 4 7 10<br/><br/>
26 29 32 35<br/><br/>
76 79 82 85</p><br/>
<p></p><br/>
<p>1&lt;=N,M&lt;=10^1000 000,a&lt;=a,b,c,d&lt;=10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

