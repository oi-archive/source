
# Description

<div class="content"><p>Byteasar bought his son Bytie a set of blocks numbered from to and arranged them in a row in a certain order. Bytie&#39;s goal is to rearrange the blocks so that they are ordered naturally, from the smallest number to the largest. However, the only moves Bytie is allowed to make are: putting the last block at the very beginning (move a), and putting the third block at the very beginning (move b). Help Bytie by writing a program that tells whether a given arrangement of blocks can be properly reordered, and tells the right sequence of moves if it is.</p>
<p>有一个1..n的排列，有两种操作：<br/>
(a) 将最后一个数移到最前面<br/>
(b) 把第三个数移到最前面<br/>
</p>
<p>我们将连续进行k次同一个操作称为“一块操作”，表示为ka或kb。<br/>
找到一个操作序列使得进行这些操作后，排列变为1,2,3,...,n。</p>
<p></p></div>

# Input

<div class="content"><p>In the first line of the standard input there is a single integer ,(1&lt;=N&lt;=2000). In the second line there are integers from the range to , separated by single spaces. No number appears twice, and thus they represent the initial arrangement of the blocks. .</p>
<p>第一行n(1&lt;=n&lt;=2000)<br/>
下面一行n个数表示这个排列。</p>
<p></p></div>

# Output

<div class="content"><p><img alt="" border="0" src="/source/bzoj/2214/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIyMTQuanBn.jpg"/> </p>
<p></p>
<p>如果不存在这样的操作序列，输出&#34;NIE DA SIE&#34;，否则<br/>
第一行m，表示操作的块数。<br/>
下面一行，表示这m块操作。<br/>
需要满足相邻两块操作的种类不同，每块操作中进行的次数大于0小于n。<br/>
需要满足m&lt;=n*n</p>
<p><br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample Input #1<br/>
4<br/>
1 3 2 4<br/>
Sample Output #1<br/>
4<br/>
3a 2b 2a 2b<br/>
<br/>
Sample Input #2<br/>
7<br/>
1 3 2 4 5 6 7<br/>
Sample Output #2<br/>
NIE DA SIE<br/>
<br/>
Sample Input #3<br/>
3<br/>
1 2 3<br/>
Sample Output #3<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>鸣谢NOIGOLD vfleaking</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

