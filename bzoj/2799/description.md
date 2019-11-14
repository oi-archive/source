
# Description

<div class="content"><p><span style="font-size: medium"><br/>
给出一棵n个结点的有根树，结点用正整数1~n编号。<br/>
每个结点有一个1~n的正整数权值，不同结点的权值不相同，<br/>
并且一个结点的权值一定比它父结点的权值大（根结点的权值最大，一定是n）。<br/>
现在有些结点的权值是已知的，并且如果一个结点的权值已知，它父结点的权值也一定已知。<br/>
问还有哪些结点的权值能够唯一确定。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行一个正整数n (n&lt;=1,000,000)，表示树的结点数。<br/>
下面共n行，第i行描述编号为i的结点，每行两个整数pi,zi (1&lt;=pi&lt;=n, 0&lt;=zi&lt;=n)。<br/>
pi表示结点i的父结点，如果i=pi，说明i是根结点。<br/>
当zi&gt;0时，表示结点i的权值已知，并且就是zi；当zi=0时，表示结点i的权值未知。<br/>
测试数据保证满足题意，并且存在合法的方案。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出共n行，依次描述每个结点。如果结点i的权值能够唯一确定，第i行输出结点i的权值，否则第i行输出0。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
2 2<br/>
2 10<br/>
1 0<br/>
2 9<br/>
2 5<br/>
4 0<br/>
6 0<br/>
6 0<br/>
5 0<br/>
5 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
10<br/>
1<br/>
9<br/>
5<br/>
8<br/>
0<br/>
0<br/>
0<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Oimaster">鸣谢Oimaster</a></p></div>

