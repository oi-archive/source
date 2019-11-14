
# Description

<div class="content"><p>　　将一个a*b的数字矩阵进行如下分割：将原矩阵沿某一条直线分割成两个矩阵，再将生成的两个矩阵继续如此<br/>
分割（当然也可以只分割其中的一个），这样分割了（n-1)次后，原矩阵被分割成了n个矩阵。（每次分割都只能<br/>
沿着数字间的缝隙进行）原矩阵中每一位置上有一个分值，一个矩阵的总分为其所含各位置上分值之和。现在需要<br/>
把矩阵按上述规则分割成n个矩阵，并使各矩阵总分的均方差最小。请编程对给出的矩阵及n，求出均方差的最小值<br/>
。</p></div>

# Input

<div class="content"><p>第一行为3个整数，表示a,b,n(1&lt;a,b&lt;=10,1&lt;n&lt;=10）的值。<br/>
第二行至第n+1行每行为b个小于100的非负整数，表示矩阵中相应位置上的分值。每行相邻两数之间用一个空<br/>
格分开。<br/>
</p></div>

# Output

<div class="content"><p>仅一个数，为均方差的最小值（四舍五入精确到小数点后2位）</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 4<br/>
2 3 4 6<br/>
5 7 5 1<br/>
10 4 0 5<br/>
2 0 2 3<br/>
4 1 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.50</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

