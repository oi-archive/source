
# Description

<div class="content"><p><span style="font-size: medium">定义一个操作，我们称为圈圈运算吧。<br/>
参加运算的是两个十进制数a和b，结果也规定是一个十进制数，输入文件将给出运算结果。特别得是：0圈圈运算0=0<br/>
如果是两个多位数进行运算 ，将按位对齐。再逐位进行运算。</span></p>
<p><span style="font-size: medium">下图按圈圈运算认为是取Mod 运算，即a圈圈运算 b=a*b mod 10</span></p>
<p><img height="84" width="522" alt="" src="/source/bzoj/2643/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8zOTYwXzEuSlBH.JPG"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">  </span><span style="font-size: medium">给出一个10行10列的数字矩阵，第一行为当a=0时，它与b的值从0取得9时，做圈圈运算的结果。最后给出两个数字M，N。代表M圈圈运算(M+1)圈圈运算(M+2)...圈圈运算(N)</span></p>
<p><span style="font-size: medium">0 &lt;= M &lt;=N &lt;= 10^18).<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出运算结果，无前置零</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">0 1 2 3 4 5 6 7 8 9<br/>
1 2 3 4 5 6 7 8 9 0<br/>
2 3 4 5 6 7 8 9 0 1<br/>
3 4 5 6 7 8 9 0 1 2<br/>
4 5 6 7 8 9 0 1 2 3<br/>
5 6 7 8 9 0 1 2 3 4<br/>
6 7 8 9 0 1 2 3 4 5<br/>
7 8 9 0 1 2 3 4 5 6<br/>
8 9 0 1 2 3 4 5 6 7<br/>
9 0 1 2 3 4 5 6 7 8<br/>
0 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
15<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

