
# Description

<div class="content"><div>
<div>小C有一个集合S，里面的元素都是小于M的非负整数。他用程序编写了一个数列生成器，可以生成一个长度为N的数</div>
<div>列，数列中的每个数都属于集合S。小C用这个生成器生成了许多这样的数列。但是小C有一个问题需要你的帮助：</div>
<div>给定整数x，求所有可以生成出的，且满足数列中所有数的乘积mod M的值等于x的不同的数列的有多少个。小C认为</div>
<div>，两个数列{Ai}和{Bi}不同，当且仅当至少存在一个整数i，满足Ai≠Bi。另外，小C认为这个问题的答案可能很大</div>
<div>，因此他只需要你帮助他求出答案mod 1004535809的值就可以了。</div>
</div></div>

# Input

<div class="content"><div>一行，四个整数，N、M、x、|S|，其中|S|为集合S中元素个数。</div>
<div>第二行，|S|个整数，表示集合S中的所有元素。</div>
<div>1&lt;=N&lt;=10^9，3&lt;=M&lt;=8000，M为质数</div>
<div>0&lt;=x&lt;=M-1，输入数据保证集合S中元素不重复<span style="font-family: arial, verdana, helvetica, sans-serif;">x∈[1,m-1]</span></div>
<p><span style="font-family: arial, verdana, helvetica, sans-serif;">集合中的数∈[0,m-1]</span></p>
<div></div></div>

# Output

<div class="content"><p>一行，一个整数，表示你求出的种类数mod 1004535809的值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 1 2<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
【样例说明】<br/>
可以生成的满足要求的不同的数列有(1,1,1,1)、(1,1,2,2)、(1,2,1,2)、(1,2,2,1)、<br/>
(2,1,1,2)、(2,1,2,1)、(2,2,1,1)、(2,2,2,2)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 感谢yts1999上传">Round 1 感谢yts1999上传</a></p></div>

