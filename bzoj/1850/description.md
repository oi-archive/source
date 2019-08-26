
# Description

<div class="content"><p>很久很久很久以前，有一个古老的主题公园，有一个伟大的工程师QDC，她打算在公园修建一个花坛，花坛周围修建一片绿化带。如果把公园看成一个M*N的矩形，也就是说把公园划分成了M*N块土地，那么绿化带和花坛可以看成一个A*B的矩形，花坛可以看成一个C*D的矩形。如图所示<br/>
20 19 18 17 16 <br/>
15 14 13 12 11 <br/>
10  9 8  7  6 <br/>
5  4  3  2  1 <br/>
QDC经过一段时间的对土地的考察，给每一块土地定了一个“肥沃度”。绿化带的肥沃度定义为A*B-C*D块土地的肥沃度的综合，她希望修建这样的一片绿化带，使得绿化带的肥沃度最大。 花坛一定要完全在绿化带的包围之中，也就是说，A*B的矩阵边上的元素一定不在C*D的举证中。 淡然，这种问题是难不倒QDC的，但是她还有别的更重要的工作要做，于是这个工作就交个你了，薪水很高的哦！<br/>
</p></div>

# Input

<div class="content"><p>第一行有六个正整数M,N,A,B,C,D。结下来M行，每行有N 个正整数，表示（i,j)的肥沃度。</p></div>

# Output

<div class="content"><p>一个正整数，表示绿化带的最大肥沃程度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 4 4 2 2<br/>
20 19 18 17 16<br/>
15 14 13 12 11<br/>
10 9 8 7 6<br/>
5 4 3 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">132<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>30%的数据， 1&lt;= m , n &lt;= 50 100%的数据, 1&lt;= m , n &lt;= 1000 100%的数据, 1&lt;= A &lt;= M 1 &lt;= B &lt;= n 1 &lt;= C &lt;= A-2 1 &lt;= D &lt;= B-2 1 &lt;= 肥沃度 &lt;= 100</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

