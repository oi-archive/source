
# Description

<div class="content"><div>给你一个n个点m条边的无向图，每条边有权值，我们可以选择一个整数lim来生成一个新的图，过程如下： </div>
<div>1.先将原图中边权小于lim的边删掉 </div>
<div>2.依次从1到n枚举每个点 </div>
<div>（a）如果这个点没有边于它相连，这个点将会被删去 </div>
<div>（b）如果这个点只与两条不相同的边x，y相连，设这两条边的另一个点分别为a，b，如果a，b和这个点都不相同（a，b可以相同），则依次做如下操作： </div>
<div>（i）删去边x，y </div>
<div>（ii）删去这个点 </div>
<div>（iii）在a，b之间建立一条新的边 </div>
<div>下面这个例子lim=95： </div>
<div><img src="/source/bzoj/4452/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMy9hYSgyKS5wbmc=.png" width="856" height="380" alt=""/></div>
<div></div>
<div>数据保证原图没有重边和自环，但不保证经过如上操作后的图没有重边和自环。 </div>
<div>现在我们想知道当lim取若干值时，由原图生成的新图的点数和边数是多少。 </div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行两个数n，m，表示原图有n点m条边。 </div>
<div>接下来m行，每行三个数a，b，c，表示a和b之间有一条边权为c的双向边。 </div>
<div>接下来一行一个数q，表示有q次询问。 </div>
<div>接下来一行q个数，k1，k2，...，kq。 </div>
<div>1&lt;=n&lt;=300000 </div>
<div>1&lt;=m&lt;=300000 </div>
<div>0&lt;=c&lt;=300000 </div>
<div>1&lt;=q&lt;=300000 </div>
<div>0&lt;=ki&lt;=300000 </div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>总共q行，每行两个数，表示lim取ki时，生成的新图的点数和边数 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample Input1: <br/>
6 7 <br/>
1 2 20 <br/>
2 3 80 <br/>
2 5 100 <br/>
3 5 50 <br/>
3 4 100 <br/>
5 6 90 <br/>
4 6 100 <br/>
4 <br/>
25 75 85 95 <br/>
Sample Input2: <br/>
10 14 <br/>
2 7 150 <br/>
1 2 100 <br/>
2 3 150 <br/>
3 1 200 <br/>
1 4 60 <br/>
4 5 20 <br/>
2 5 100 <br/>
5 6 90 <br/>
6 7 120 <br/>
7 5 130 <br/>
6 8 50 <br/>
8 9 200 <br/>
9 10 200 <br/>
10 7 200 <br/>
5 <br/>
300 50 95 100 110 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample Output1: <br/>
2 3 <br/>
1 1 <br/>
2 1 <br/>
4 2 <br/>
Sample Output2: <br/>
0 0 <br/>
6 9 <br/>
4 5 <br/>
4 5 <br/>
5 4 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

