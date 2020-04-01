
# Description

<div class="content"><div>在2016年，佳媛姐姐喜欢上了数字序列。因而他经常研究关于序列的一些奇奇怪怪的问题，现在他在研究一个难题</div>
<div>，需要你来帮助他。这个难题是这样子的：给出一个1到n的全排列，现在对这个全排列序列进行m次局部排序，排</div>
<div>序分为两种：1:(0,l,r)表示将区间[l,r]的数字升序排序2:(1,l,r)表示将区间[l,r]的数字降序排序最后询问第q</div>
<div>位置上的数字。</div></div>

# Input

<div class="content"><div>输入数据的第一行为两个整数n和m。n表示序列的长度，m表示局部排序的次数。1 &lt;= n, m &lt;= 10^5第二行为n个整</div>
<div>数，表示1到n的一个全排列。接下来输入m行，每一行有三个整数op, l, r, op为0代表升序排序，op为1代表降序</div>
<div>排序, l, r 表示排序的区间。最后输入一个整数q，q表示排序完之后询问的位置, 1 &lt;= q &lt;= n。1 &lt;= n &lt;= 10^5</div>
<div>，1 &lt;= m &lt;= 10^5</div>
<div></div></div>

# Output

<div class="content"><p> 输出数据仅有一行，一个整数，表示按照顺序将全部的部分排序结束后第q位置上的数字。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 6 2 5 3 4<br/>
0 1 4<br/>
1 3 6<br/>
0 2 4<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

