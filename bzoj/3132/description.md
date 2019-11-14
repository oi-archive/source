
# Description

<div class="content"><p><span style="font-size: medium">“第一分钟，X说，要有矩阵，于是便有了一个里面写满了0的n×m矩阵。</span></p>
<p><span style="font-size: medium">第二分钟，L说，要能修改，于是便有了将左上角为(a,b)，右下角为(c,d)的一个矩形区域内的全部数字加上一个值的操作。</span></p>
<p><span style="font-size: medium">第三分钟，k说，要能查询，于是便有了求给定矩形区域内的全部数字和的操作。</span></p>
<p><span style="font-size: medium">第四分钟，彩虹喵说，要基于二叉树的数据结构，于是便有了数据范围。</span></p>
<p><span style="font-size: medium">第五分钟，和雪说，要有耐心，于是便有了时间限制。</span></p>
<p><span style="font-size: medium">第六分钟，吃钢琴男说，要省点事，于是便有了保证运算过程中及最终结果均不超过32位有符号整数类型的表示范围的限制。</span></p>
<p><span style="font-size: medium">第七分钟，这道题终于造完了，然而，造题的神牛们再也不想写这道题的程序了。”</span></p>
<p><span style="font-size: medium">       ——《上帝造裸题的七分钟》</span></p>
<p><span style="font-size: medium">所以这个神圣的任务就交给你了。</span></p>
<p></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"> 输入数据的第一行为X n m，代表矩阵大小为n×m。</span></p>
<p><span style="font-size: medium">从输入数据的第二行开始到文件尾的每一行会出现以下两种操作：</span></p>
<p><span style="font-size: medium">　　L a b c d delta —— 代表将(a,b),(c,d)为顶点的矩形区域内的所有数字加上delta。</span></p>
<p><span style="font-size: medium">　　k a b c d　　 —— 代表求(a,b),(c,d)为顶点的矩形区域内所有数字的和。</span></p>
<p> </p>
<p><span style="font-size: medium">请注意，k为小写。</span></p>
<p><span style="font-size: medium"><br/>
         </span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">针对每个k操作，在单独的一行输出答案。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">X 4 4<br/>
L 1 1 3 3 2<br/>
L 2 2 4 4 1<br/>
k 2 2 3 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据，1 ≤ n ≤ 2048, 1 ≤ m ≤ 2048, 1 ≤ abs(delta) ≤ 500,操作不超过200000个,保证运算过程中及最终结果均不超过32位带符号整数类型的表示范围。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=tyvj">tyvj</a></p></div>

