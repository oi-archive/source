
# Description

<div class="content"><p><span style="font-size: medium"><br/>
为了使得大家高兴，小Q特意出个自认为的简单题（easy）来满足大家，这道简单题是描述如下：<br/>
有一个数列A已知对于所有的A[i]都是1~n的自然数，并且知道对于一些A[i]不能取哪些值，我们定义一个数列的积为该数列所有元素的乘积，要求你求出所有可能的数列的积的和 mod 1000000007的值，是不是很简单呢？呵呵！<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">第一行三个整数n,m,k分别表示数列元素的取值范围，数列元素个数，以及已知的限制条数。<br/>
接下来k行，每行两个正整数x,y表示A[x]的值不能是y。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">一行一个整数表示所有可能的数列的积的和对1000000007取模后的结果。如果一个合法的数列都没有，答案输出0。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 5<br/>
1 1<br/>
1 1<br/>
2 2<br/>
2 3<br/>
4 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">90<br/>
样例解释<br/>
A[1]不能取1<br/>
A[2]不能去2、3<br/>
A[4]不能取3<br/>
所以可能的数列有以下12种<br/>
数列      积<br/>
2 1 1 1     2<br/>
2 1 1 2     4<br/>
2 1 2 1     4<br/>
2 1 2 2     8<br/>
2 1 3 1     6<br/>
2 1 3 2     12<br/>
3 1 1 1     3<br/>
3 1 1 2     6<br/>
3 1 2 1     6<br/>
3 1 2 2     12<br/>
3 1 3 1     9<br/>
3 1 3 2     18<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围<br/><br/>
30%的数据n&lt;=4,m&lt;=10,k&lt;=10<br/><br/>
另有20%的数据k=0<br/><br/>
70%的数据n&lt;=1000,m&lt;=1000,k&lt;=1000<br/><br/>
100%的数据 n&lt;=109,m&lt;=109,k&lt;=105,1&lt;=y&lt;=n,1&lt;=x&lt;=m<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

