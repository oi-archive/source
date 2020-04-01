
# Description

<div class="content"><div>Autumn和Bakser又在研究Gty的妹子序列了！但他们遇到了一个难题。</div>
<div></div>
<div>对于一段妹子们，他们想让你帮忙求出这之内美丽度∈[a,b]的妹子的美丽度的种类数。</div>
<div></div>
<div>为了方便，我们规定妹子们的美丽度全都在[1,n]中。</div>
<div></div>
<div>给定一个长度为n(1&lt;=n&lt;=100000)的正整数序列s(1&lt;=si&lt;=n)，对于m(1&lt;=m&lt;=1000000)次询问“l,r,a,b”，每次输出sl...sr中，权值∈[a,b]的权值的种类数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括两个整数n,m(1&lt;=n&lt;=100000,1&lt;=m&lt;=1000000),表示数列s中的元素数和询问数。</div>
<div></div>
<div>第二行包括n个整数s1...sn(1&lt;=si&lt;=n)。</div>
<div></div>
<div>接下来m行,每行包括4个整数l,r,a,b(1&lt;=l&lt;=r&lt;=n,1&lt;=a&lt;=b&lt;=n),意义见题目描述。</div>
<div></div>
<div>保证涉及的所有数在C++的int内。</div>
<div></div>
<div>保证输入合法。</div>
<p></p></div>

# Output

<div class="content"><p>对每个询问，单独输出一行，表示sl...sr中权值∈[a,b]的权值的种类数。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10<br/>
4 4 5 1 4 1 5 1 2 1<br/>
5 9 1 2<br/>
3 4 7 9<br/>
4 4 2 5<br/>
2 3 4 7<br/>
5 10 4 4<br/>
3 9 1 1<br/>
1 4 5 9<br/>
8 9 3 3<br/>
2 2 1 6<br/>
8 9 1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
0<br/>
2<br/>
1<br/>
1<br/>
1<br/>
0<br/>
1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><div>样例的部分解释：</div><br/>
<div></div><br/>
<div>5 9 1 2</div><br/>
<div>子序列为4 1 5 1 2</div><br/>
<div>在[1,2]里的权值有1,1,2，有2种，因此答案为2。</div><br/>
<div></div><br/>
<div>3 4 7 9</div><br/>
<div>子序列为5 1</div><br/>
<div>在[7,9]里的权值有5，有1种，因此答案为1。</div><br/>
<div></div><br/>
<div>4 4 2 5</div><br/>
<div>子序列为1</div><br/>
<div>没有权值在[2,5]中的，因此答案为0。</div><br/>
<div></div><br/>
<div>2 3 4 7</div><br/>
<div>子序列为4 5</div><br/>
<div>权值在[4,7]中的有4,5，因此答案为2。</div><br/>
<div></div><br/>
<div>建议使用输入/输出优化。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

