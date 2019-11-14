
# Description

<div class="content"><div><span style="font-size: medium">在膜拜sone神题之余，Stilwell决定出一道福利题</span></div>
<div><span style="font-size: medium">Stilwell等弱菜开始讨论矩阵的问题</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">Memphis：矩阵加减不是特水，矩阵求和显然是应该有的</span></div>
<div><span style="font-size: medium">Wwt:轴对称变换，平移操作不是超有趣</span></div>
<div><span style="font-size: medium">Yzh：单点修改也加上</span></div>
<div><span style="font-size: medium">Ly：可以把矩阵输出玩一下</span></div>
<div><span style="font-size: medium">Stilwell：旋转操作不是挺逗</span></div>
<div><span style="font-size: medium">……</span></div>
<div><span style="font-size: medium">最后，Stilwell等人发现自己太弱了，于是请花老师秒出了标程</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">第一行是一个整数N表示，有一个N*N的矩阵</span></div>
<div><span style="font-size: medium">从输入数据的第二行开始到文件尾的每一行会出现以下几种操作：</span></div>
<div><span style="font-size: medium">L a b c d delta —— 代表将(a,b),(c,d)为顶点的矩形区域内的所有数字加上delta。</span></div>
<div><span style="font-size: medium">k a b c d　　   —— 代表求(a,b),(c,d)为顶点的矩形区域内所有数字的和。</span></div>
<div><span style="font-size: medium">Fx              —— 代表这个图形绕x轴中心翻转，如下：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">原矩阵：           操作后：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">1 2 3               3 2 1</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">4 5 6               6 5 4</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">7 8 9               9 8 7</span></div>
<div><span style="font-size: medium">Fy              —— 代表这个图形绕y轴中心翻转，如下：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">原矩阵：           操作后：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">1 2 3               7 8 9</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">4 5 6               4 5 6</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">7 8 9               1 2 3</span></div>
<div><span style="font-size: medium">Dx a            —— 代表这个图形沿x轴平移a个单位，如下：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">原矩阵：           操作后：（Dy 1）（a可能为负）</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">1 2 3               7 8 9</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">4 5 6               1 2 3</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">7 8 9               4 5 6</span></div>
<div><span style="font-size: medium">Dy a            —— 代表这个图形沿y轴平移a个单位，如下：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">原矩阵：           操作后：（Dy 1）（a可能为负）</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">1 2 3               3 1 2</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">4 5 6               6 4 5</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">7 8 9               9 7 8</span></div>
<div><span style="font-size: medium">R+              —— 代表这个图形顺时针旋转90°，如下：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">原矩阵：           操作后：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">1 2 3               7 4 1</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">4 5 6               8 5 2</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">7 8 9               9 6 3</span></div>
<div><span style="font-size: medium">R-              —— 代表这个图形逆时针旋转90°，如下：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">原矩阵：           操作后：</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">1 2 3               3 6 9</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">4 5 6               2 5 8</span></div>
<div style="text-indent: 110.25pt"><span style="font-size: medium">7 8 9               1 4 7</span></div>
<div><span style="font-size: medium">C a b delta    —— 代表这个点的值改为delta</span></div>
<div><span style="font-size: medium">Q              —— 代表把当前的整个矩阵输出</span></div>
<div><span style="font-size: medium">请注意，沿用《上帝造题的七分钟》，k为小写。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">注：读入矩阵时，第I行第j个表示坐标（x,y）为（I,j）的点</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">对于每一个k，在单独一行输出一个答案</span></div>
<div><span style="font-size: medium">对于每一个Q，输出整个矩阵</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
L 1 1 1 1 1<br/>
L 1 2 1 2 2<br/>
L 2 1 2 1 3<br/>
L 2 2 2 2 3<br/>
C 2 2 4<br/>
Fx<br/>
R-<br/>
k 1 2 2 2<br/>
Dy 1<br/>
k 1 2 2 2<br/>
Q</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
3<br/>
3 1<br/>
4 2<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1 ≤ n ≤ 1024 , |delta| ≤ 100,操作不超过200000个,保证运算过程中及最终结果均不超过32位带符号整数类型的表示范围，保证Q操作输出总数不超过3000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

