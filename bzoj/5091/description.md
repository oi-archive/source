
# Description

<div class="content"><div>小Q的工作是采摘花园里的苹果。在花园中有n棵苹果树以及m条双向道路，苹果树编号依次为1到n，每条道路的两</div>
<div>端连接着两棵不同的苹果树。假设第i棵苹果树连接着d_i条道路。小Q将会按照以下方式去采摘苹果：</div>
<div></div>
<div>1.小Q随机移动到一棵苹果树下，移动到第i棵苹果树下的概率为d_i/(2m)，但不在此采摘。</div>
<div></div>
<div>2.等概率随机选择一条与当前苹果树相连的一条道路，移动到另一棵苹果树下。</div>
<div></div>
<div>3.假设当前位于第i棵苹果树下，则他会采摘a_i个苹果，多次经过同一棵苹果树下会重复采摘。</div>
<div></div>
<div>4.重复第2和3步k次。</div>
<div></div>
<div>请写一个程序帮助计算小Q期望摘到多少苹果。</div>
<div></div></div>

# Input

<div class="content"><p>第一行包含三个正整数n,m,k(n,k&lt;=100000,m&lt;=200000)，分别表示苹果树和道路的数量以及重复步骤的次数。</p>
<div>第二行包含n个正整数，依次表示a_1,a_2,...,a_n(1&lt;=a_i&lt;=100)。</div>
<div>接下来m行，每行两个正整数u,v(1&lt;=u,v&lt;=n,u!=v)，表示第u和第v棵苹果树之间存在一条道路。</div>
<div></div>
<div></div></div>

# Output

<div class="content"><p> 若答案为P/Q，则输出一行一个整数，即P*Q^{-1} mod 1000000007(10^9+7)。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 2<br/>
2 3 4<br/>
1 2<br/>
1 2<br/>
2 3<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">750000011<br/>
//期望为5.75=23/4=(23*250000002) mod 1000000007=750000011。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

