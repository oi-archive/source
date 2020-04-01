
# Description

<div class="content"><div>WJJ喜欢旅游，这次她打算去一个据说有很多漂亮瀑布的山谷玩。</div>
<div>WJJ事先得到了一张地图，上面标注了N(1&lt; = N&lt; = 50)个小动物的聚居地，也就是一个个的小村落。其中第1个村</div>
<div>庄是WJJ现在住的地方，第N个村庄是WJJ打算去的地方。这些村庄之间有M(1&lt; = M&lt; = 150)条双向道路连接着，第j</div>
<div>条双向道路恰好直接连接两个小村庄A，B，长度为C(1&lt; = A，B &lt; = N，Ai&lt;&gt;B, 1&lt; = C&lt; = 1000)。道路有的是隧</div>
<div>道，有的是栈桥，地图上那些看起来在村庄之外交叉的路实际上并不相交——也就是说，如果把这些小村落和双向</div>
<div>道路构成的道路网看作图论意义上的图，我们不保证它是平面图，也不保证它没有重边。不过，有一点还是可以保</div>
<div>证的：WJJ细心地验证过，从它居住的村落一定能走到她想去的那个山谷。</div>
<div>在WJJ所在的神奇世界中，每只小动物都可以借助仙人掌来施放魔法，其中之一是，交换世界中任意两条双向道路</div>
<div>的长度，同时保持其他道路的长度不变。按WJJ目前的魔法水平，她最多能使用K(1&lt; = K&lt; = 20)次这种道路长度交</div>
<div>换魔法。可惜的是，由于仙人掌刺比较多，WJJ并不打算带着它旅行，于是她会在家里完成想要的道路交换后再出</div>
<div>门。假设WJI的旅行途中不会有其他小动物进行道路交换来破坏她设计好的路线。为了尽快达到目的地，WJJ希望她</div>
<div>需要走的总距离越短越好。也就是说，使用最多K次魔法后，从村落1到村落N的最短距离是多少？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行：3个用空格隔开的整数N，M，K</div>
<div>第2．．M+1行：每行是3个整数，用空格隔开，分别表示A，B C</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>1个整数，表示使用最多K次魔法后，村落1和村落N之间的最短距离。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5  5  2<br/>
1  2  10<br/>
2  5  10<br/>
1  3  4<br/>
3  4  2<br/>
4  5  1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
一个可行的方案是，对调第1条边和第4条边的长度，再对调第1条边和第5条边的长度。对调后的最短路径为1--&gt;2-<br/>
-&gt;5，长度为3。显然没有比这更优的方案了。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

