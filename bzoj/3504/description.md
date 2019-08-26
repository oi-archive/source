
# Description

<div class="content"><p><span style="font-size: medium">Alice和Bob居住在一个由N座岛屿组成的国家，岛屿被编号为0到N-1。某些岛屿之间有桥相连，桥上的道路是双<br/>
向的，但一次只能供一人通行。其中一些桥由于年久失修成为危桥，最多只能通行两次。Alice希望在岛屿al和a2之间往返an次（从al到a2再从a2到al算一次往返）。同时，Bob希望在岛屿bl和b2之间往返bn次。这个过程中，所有危桥最多通行两次，其余的桥可以无限次通行。请问Alice和Bob能完成他们的愿望吗？<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">本题有多组测试数据。<br/>
每组数据第一行包含7个空格隔开的整数，分别为N、al、a2、an、bl、b2、bn。<br/>
接下来是一个N行N列的对称矩阵，由大写字母组成。矩阵的i行j列描述编号i一1和j-l的岛屿间的连接情况，若为“O”则表示有危桥相连：为“N”表示有普通的桥相连：为“X”表示没有桥相连。<br/>
|</font></p></div>

# Output

<div class="content"><p><font size="4">对于每组测试数据输出一行，如果他们都能完成愿望输出“Yes”，否则输出“No”。</font></p>
<p></p>
<p><br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 0 1 1 2 3 1<br/>
XOXX<br/>
OXOX<br/>
XOXO<br/>
XXOX<br/>
4 0 2 1 1 3 2<br/>
XNXO<br/>
NXOX<br/>
XOXO<br/>
OXOX<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
数据范围<br/>
 4&lt;=N&lt;50<br/>
 O&lt;=a1, a2, b1, b2&lt;=N-1<br/>
 1 &lt;=an.  b&lt;=50<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

