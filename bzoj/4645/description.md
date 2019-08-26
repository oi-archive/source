
# Description

<div class="content"><div>图的定义：图G是一个有序二元组(V,E)，其中V称为顶集，E称为边集，</div>
<div>E与V不相交。它们亦可写成V(G)和E(G)。</div>
<div>此题中图不允许有重边和自环。</div>
<div>树的定义：树是一种特殊的图，它是一个连通图，且任意删去一条边，它</div>
<div>就不连通。</div>
<div>两个图同构的定义：</div>
<div>设这两个图为G1=(VI，E1)，G2=(V2，E2)</div>
<div>1．点数相同。</div>
<div>2．如果是一个有标号的图，那么他们同构等价于E1=E2。</div>
<div>3．如果是一个无标号的图，且存在一种对于Gl和G2的标号使得新的两个有</div>
<div>标号图同构，那么它们同构。</div>
<div>问题描述：</div>
<div>1．给定一个整数n，求n个点的有标号的无根树的个数。</div>
<div>2．给定一个整数n，求n个点的有标号的有根树的个数。</div>
<div>3．给定一个整数n，求n个点的无标号的无根树的个数。</div>
<div>4．给定一个整数n，求n个点的无标号的有根树酌个数。</div>
<div>5．给定一个整数n，求n个点的有标号的所有点的度数均为偶数的图的个数。</div>
<div>6．给定一个整数n，求n个点的有标号的欧拉图的个数。</div>
<div>7．给定一个整数n，求n个点的有标号的二分图的个数。</div>
<div>求方案数对m取模的结果。保证m是质数。</div>
<div></div></div>

# Input

<div class="content"><div>
<div>一行八个数m，nl，n2，n3，n4，n5，n6，n7，分别为原问题中的m和七个问题</div>
<div>1&lt; nl，n2，n5&lt;10^18，n3，n4，n6，n7≤1000，l&lt;m&lt;10^9</div>
</div>
<div></div></div>

# Output

<div class="content"><div>一行七个数，表示七个问题的答案。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 2 2 2 2 2 2 2    </span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2 1 1 1 0 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

