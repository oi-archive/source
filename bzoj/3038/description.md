
# Description

<div class="content"><p><span style="font-size: medium">XLk觉得《上帝造题的七分钟》不太过瘾，于是有了第二部。<br/>
&#34;第一分钟，X说，要有数列，于是便给定了一个正整数数列。<br/>
第二分钟，L说，要能修改，于是便有了对一段数中每个数都开平方(下取整)的操作。<br/>
第三分钟，k说，要能查询，于是便有了求一段数的和的操作。<br/>
第四分钟，彩虹喵说，要是noip难度，于是便有了数据范围。<br/>
第五分钟，诗人说，要有韵律，于是便有了时间限制和内存限制。<br/>
第六分钟，和雪说，要省点事，于是便有了保证运算过程中及最终结果均不超过64位有符号整数类型的表示范围的限制。<br/>
第七分钟，这道题终于造完了，然而，造题的神牛们再也不想写这道题的程序了。&#34;<br/>
——《上帝造题的七分钟·第二部》<br/>
所以这个神圣的任务就交给你了。<br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个整数n，代表数列中数的个数。<br/>
第二行n个正整数，表示初始状态下数列中的数。<br/>
第三行一个整数m，表示有m次操作。<br/>
接下来m行每行三个整数k,l,r，k=0表示给[l,r]中的每个数开平方(下取整)，k=1表示询问[l,r]中各个数的和。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于询问操作，每行输出一个回答。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1 2 3 4 5 6 7 8 9 10<br/>
5<br/>
0 1 10<br/>
1 1 10<br/>
1 1 5<br/>
0 5 8<br/>
1 4 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">19<br/>
7<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><p><font size="4">1：对于100%的数据，1&lt;=n&lt;=100000，1&lt;=l&lt;=r&lt;=n，数列中的数大于0，且不超过1e12。</font></p><br/>
<p><font size="4">2：数据不保证L&lt;=R 若L&gt;R，请自行交换L,R，谢谢！ </font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize4">Poetize4</a></p></div>

