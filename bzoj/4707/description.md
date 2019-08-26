
# Description

<div class="content"><div>给出一个n，保证n=2^K（K为整数），和一个n*n的方阵Wi,j保证Wi,j=0(0≤i&lt;n)且Wi,j=Wj,i(0≤i，j&lt;n)求出一个</div>
<div>0，1…n一1的排列Pi，使得∑(Wpi-1,Pi)最小。但是这个排列还要满足一个特殊的条件：那就是对于所有的j(0≤J</div>
<div>≤K，从前往后分成2^(K-j)块，每块长度2^j，对于任意一块i，包含Pi2^<sup>j</sup>，Pi2^<sup>j+1</sup>，…，P(i+1)2^<sup>j-1</sup>，这些数</div>
<div>的二进制第J位（最低位是第0位）都一样。比如3，2，0，1是满足条件的，而3，0，1，2不满足因为当j=l时，分</div>
<div>成的第一块3，0的第j=l位不相等，3的第1位是1而0的第1位是0。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个K。从第二行开始，一个n×n的矩阵。</div>
<div>2&lt;=k&lt;=9,矩阵是关于主对角线对称的，每一项Wi,j在[0,1000000]</div>
<p></p></div>

# Output

<div class="content"><div>第一行一个整数表示答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
0 7 2 1<br/>
7 0 4 3<br/>
2 4 0 5<br/>
1 3 5 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">13<br/>
【样例解释】<br/>
序列为1，0，3，2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

