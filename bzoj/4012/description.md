
# Description

<div class="content"><p> 风见幽香有一个好朋友叫八云紫，她们经常一起看星星看月亮从诗词歌赋谈到</p>
<div>人生哲学。最近她们灵机一动，打算在幻想乡开一家小店来做生意赚点钱。这样的</div>
<div>想法当然非常好啦，但是她们也发现她们面临着一个问题，那就是店开在哪里，面</div>
<div>向什么样的人群。很神奇的是，幻想乡的地图是一个树形结构，幻想乡一共有 n</div>
<div>个地方，编号为 1 到 n，被 n-1 条带权的边连接起来。每个地方都住着一个妖怪，</div>
<div>其中第 i 个地方的妖怪年龄是 x_i。妖怪都是些比较喜欢安静的家伙，所以它们并</div>
<div>不希望和很多妖怪相邻。所以这个树所有顶点的度数都小于或等于 3。妖怪和人一</div>
<div>样，兴趣点随着年龄的变化自然就会变化，比如我们的 18 岁少女幽香和八云紫就</div>
<div>比较喜欢可爱的东西。幽香通过研究发现，基本上妖怪的兴趣只跟年龄有关，所以</div>
<div>幽香打算选择一个地方 u（u为编号），然后在 u开一家面向年龄在 L到R 之间（即</div>
<div>年龄大于等于 L、小于等于 R）的妖怪的店。也有可能 u这个地方离这些妖怪比较</div>
<div>远，于是幽香就想要知道所有年龄在 L 到 R 之间的妖怪，到点 u 的距离的和是多</div>
<div>少（妖怪到 u 的距离是该妖怪所在地方到 u 的路径上的边的权之和） ，幽香把这个</div>
<div>称为这个开店方案的方便值。幽香她们还没有决定要把店开在哪里，八云紫倒是准</div>
<div>备了很多方案，于是幽香想要知道，对于每个方案，方便值是多少呢。</div>
<div></div></div>

# Input

<div class="content"><p> 第一行三个用空格分开的数 n、Q和A，表示树的大小、开店的方案个数和妖</p>
<div>怪的年龄上限。 </div>
<div>第二行n个用空格分开的数 x_1、x_2、…、x_n，x_i 表示第i 个地点妖怪的年</div>
<div>龄，满足0&lt;=x_i&lt;A。(年龄是可以为 0的，例如刚出生的妖怪的年龄为 0。) </div>
<div>接下来 n-1 行，每行三个用空格分开的数 a、b、c，表示树上的顶点 a 和 b 之</div>
<div>间有一条权为c(1 &lt;= c &lt;= 1000)的边，a和b 是顶点编号。 </div>
<div>接下来Q行，每行三个用空格分开的数 u、 a、 b。对于这 Q行的每一行，用 a、</div>
<div>b、A计算出 L和R，表示询问“在地方 u开店，面向妖怪的年龄区间为[L,R]的方</div>
<div>案的方便值是多少”。对于其中第 1 行，L 和 R 的计算方法为：L=min(a%A,b%A), </div>
<div>R=max(a%A,b%A)。对于第 2到第 Q行，假设前一行得到的方便值为 ans，那么当</div>
<div>前行的 L 和 R 计算方法为： L=min((a+ans)%A,(b+ans)%A), </div>
<div>R=max((a+ans)%A,(b+ans)%A)。 </div>
<div></div></div>

# Output

<div class="content"><p>对于每个方案，输出一行表示方便值。 </p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 10 10 <br/>
0 0 7 2 1 4 7 7 7 9  <br/>
1 2 270 <br/>
2 3 217 <br/>
1 4 326 <br/>
2 5 361 <br/>
4 6 116 <br/>
3 7 38 <br/>
1 8 800 <br/>
6 9 210 <br/>
7 10 278 <br/>
8 9 8 <br/>
2 8 0 <br/>
9 3 1 <br/>
8 0 8 <br/>
4 2 7 <br/>
9 7 3 <br/>
4 7 0 <br/>
2 2 7 <br/>
3 2 1 <br/>
2 3 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1603 <br/>
957 <br/>
7161 <br/>
9466 <br/>
3232 <br/>
5223 <br/>
1879 <br/>
1669 <br/>
1282 <br/>
0 </span></div>

# Hint

<div class="content"><p></p><p> 满足 n&lt;=150000,Q&lt;=200000。对于所有数据，满足 A&lt;=10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

