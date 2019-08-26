
# Description

<div class="content"><p><span style="font-size: medium"> 我们称一个长度为2n的数列是有趣的，当且仅当该数列满足以下三个条件：</span></p>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> (1)它是从1到2n共2n个整数的一个排列{a<sub>i</sub>}；</span></p>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> (2)所有的奇数项满足a<sub>1</sub>&lt;a<sub>3</sub>&lt;…&lt;a<sub>2n-1</sub>，所有的偶数项满足a<sub>2</sub>&lt;a<sub>4</sub>&lt;…&lt;a<sub>2n</sub>；</span></p>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> (3)任意相邻的两项a<sub>2i-1</sub>与a<sub>2i</sub>(1≤i≤n)满足奇数项小于偶数项，即：a<sub>2i-1</sub>&lt;a<sub>2i</sub>。</span></p>
<p><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> </span><wbr/><span style="font-size: medium"> 现在的任务是：对于给定的n，请求出有多少个不同的长度为2n的有趣的数列。因为最后的答案可能很大，所以只要求输出答案 mod P的值。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入文件只包含用空格隔开的两个整数n和P。输入数据保证，50%的数据满足n≤1000，100%的数据满足n≤1000000且P≤1000000000。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">仅含一个整数，表示不同的长度为2n的有趣的数列个数mod P的值。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">    3 10                  </span></div>

# Sample Output

<div class="content"><span class="sampledata">  5<br/>
<br/>
<br/>
    对应的5个有趣的数列分别为（1,2,3,4,5,6），（1,2,3,5,4,6），（1,3,2,4,5,6），（1,3,2,5,4,6），（1,4,2,5,3,6）。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

