
# Description

<div class="content"><div>首先定义一种建图的方式，先选出一个常数C表示颜色的种类数，然后要建出一个含n个点的仙人掌，一开始图中一</div>
<div>共n连通块，n个点，没有边，每个点初始颜色均为1，你有如下3种操作可以使用：</div>
<div>1、join a b：将a所在的连通块和b所在的连通块划分为同一个连通块，不在a和b之间连边，必须保证a和b不能在同一个连通块。</div>
<div>2、recolor a c1 c2：将a所在的连通块中所有颜色为c1的点的颜色都改成c2。</div>
<div>3、connect a c1 c2：将a所在的连通块中颜色为c1的点和颜色为c2的点之间互相连边，如果c1=c2，则重边不连，</div>
<div>如果两个要连边的点已经连了一条边，则该次操作仍会在这两个点之间连边（当然重边是不允许出现在仙人掌中的</div>
<div>，所以你必须设法避免这种情况）。</div>
<div>给出最后构成的仙人掌，请你在保证C最小（保证C最大不会超过4）的情况下，输出构造方案。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n（n&lt;=50000,m&lt;=50000)，表示最后构成的仙人掌有n个点，m条路径。</div>
<div>接下来m行，每行第一个数x(x&lt;=1000),紧接着x个数，表示一条路径。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行输出一个数q，表示操作次数。</div>
<div>接下来q行每行第一个输出一个字母：j或r或c，分别表示以上三种操作的第1、2、3种</div>
<div>若第一个字母为j，则接下来两个数a,b，含义如上所示</div>
<div>若第一个字母为r或c，则接下来三个数a,c1,c2，含义如上所述。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 2<br/>
5 1 2 3 4 7<br/>
5 4 5 6 1 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
r 2 1 2<br/>
j 2 3<br/>
c 2 1 2<br/>
r 6 1 2<br/>
j 5 6<br/>
c 6 1 2<br/>
r 4 1 3<br/>
j 4 3<br/>
j 4 6<br/>
j 4 7<br/>
c 4 3 1<br/>
r 4 3 1<br/>
r 8 1 2<br/>
r 1 1 3<br/>
j 1 8<br/>
j 1 4<br/>
c 1 3 2</span></div>

# Hint

<div class="content"><p></p><p> 请不要提交！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

