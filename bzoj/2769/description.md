
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">友爱的YY小朋友,正在学习快速排序，聪明的他很快就发现，快排是会出现退化的情况的。于是乎他友爱地发明了用随机化的方法。但是这个时候友爱的小YY还是不满足于现状，他想知道怎么证明快速排序的期望复杂度是O(nlogn)。于是他决定自己定义代价自己算，他的快速排序过程是这样的：首先在待排序的数字里随机选取一个X作为基准点,然后代价变量S=划分代价（<b>划分代价即在</b><b>X</b><b>的左边比X</b><b>大的数字的个数+</b><b>在X</b><b>的右边比X</b><b>小的数字的个数</b>）+将两部分分别递归下去的S。<b>划分的过程中保持相对位置不变。</b>聪明又友爱的他很快就发现S的最大期望是nlogn的级别的，但是好学的他还想知道对于一个具体的，数字不重复的序列，S的期望是多少。当然你要知道YY是要拿UOI金牌的人，所以他决定让你来完成计算的工作。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第一行一个整数n。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第二行n个整数，表示待排序数列（每个数字均在long范围内）。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">一个实数,S的期望值。（保留六位小数）</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">输入样例</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">3</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">1 2 3</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
0.000000<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>数据规模<br/><br/>
20%的数据保证1&lt;=n&lt;=300<br/><br/>
100%的数据保证1&lt;=n&lt;=15000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

