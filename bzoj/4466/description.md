
# Description

<div class="content"><p>超立方体是立方体在高维空间内的拓展（其在 2 维情况下退化为正方形，1<br/>
维情况下退化成线段）。在理论计算机科学领域里，超立方体往往可以和 2 进制<br/>
编码联系到一起。对理论计算机科学颇有研究的 Will 自然也会对超立方体有着<br/>
自己的思考。 <br/>
<img width="471" height="209" alt="" src="/source/bzoj/4466/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8xMSgxKS5wbmc=.png"/><br/>
上图就是在 0～4 维空间内超立方体所对应的图形。显然我们可以把超立方<br/>
体的每个顶点看成一个点，每一条棱看成一条边，这样就会得到一个无向图，我<br/>
们称之为超立方图。 <br/>
D维空间内的超立方图有 2D个点，我们把这些点从0到2D-1依次编号。 <br/>
有一个有趣而重要的充要结论是：一定存在一种编号的方式，使得图中任意<br/>
两个有边相连的顶点的编号的 2进制码中，恰好有一位不同。 <br/>
在 2维和3维空间内这个结论可以这样形象的理解： <br/>
对于 2维空间，我们只要把这个正方形放到第一象限内，使得 4个顶点的坐<br/>
标按逆时针顺序依次为(0,0)，(1,0)，(1,1)，(0,1)，然后再把坐标看成 2位2进制<br/>
数，依次将这 4个点编号为 0，1，3，2即可。 <br/>
对于 3维空间，同样我们可以将立方体的一个顶点与原点重合，并使得所有<br/>
棱均平行于坐标轴，然后分别确定这8个点的坐标，最后把3维空间内的坐标看<br/>
成一个3位2进制数即可。对于D维空间，以此类推。 <br/>
现在对于一个 N 个点M条边的无向图（每个点从 0到N-1编号），Will 希望<br/>
知道这个图是否同构于一个超立方图。</p></div>

# Input

<div class="content"><p>第一行包含一个整数 Q表示此数据中一共包含 Q个询问。<br/>
接下来 Q组询问，每一组询问的输入格式如下：<br/>
第一行包含两个整数 N 和M，<br/>
接下来 M 行，每行 2 个不同的整数 x，y，表示图中存在一条无向边连接编<br/>
号为x和y的点（0 &lt; = x,y &lt; N）<br/>
Q&lt;=3,N&lt;=32768,M&lt;=1000000</p></div>

# Output

<div class="content"><p>对于每一个询问分别输出一行，内容如下： <br/>
1、如果询问中给定的图不同构于任何一个超立方图，输出-1； <br/>
2、如果同构于某一个超立方图，那么请给图中这N 个点重新编号，并在这<br/>
一行输出 N 个用空格隔开的整数，表示原图中每个点新的编号，使得重新编号<br/>
后，满足题目中所述的结论。 <br/>
注意：输出文件的每一行，要么仅包含一个整数-1，要么则应包含一个由 0<br/>
到N-1这 N 个数组成的排列。如果有多组解输出任意一个均可。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 2<br/>
0 1<br/>
1 0<br/>
4 4<br/>
0 1<br/>
1 2<br/>
2 0<br/>
0 3<br/>
8 12<br/>
2 3<br/>
2 6<br/>
7 6<br/>
1 7<br/>
4 1<br/>
3 4<br/>
0 2<br/>
7 3<br/>
5 6<br/>
5 1<br/>
5 0<br/>
4 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">-1<br/>
-1<br/>
0 6 1 5 4 2 3 7<br/>
【样例说明】<br/>
超立方图中显然是不能有重边的，所以第一个样例是无解的。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传 鸣谢ScarletMoon提供SPJ">By 佚名上传 鸣谢ScarletMoon提供SPJ</a></p></div>

