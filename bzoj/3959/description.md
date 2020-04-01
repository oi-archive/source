
# Description

<div class="content"><div>上周Tess L. Ation在演示她的绘图软件的时候遇到了一些麻烦。她用了几个小时的时间制作了一个精美的演示图形，展示了软件的所有功能。在制作快要结束的时候，一群潜在的投资者进入了房间来观看演示。</div>
<div></div>
<div>演示的进展非常顺利。快结束的时候，Tess点击了一个按钮并告诉她的观众：“这是“转到格点”功能。它可以让控制点（例如顶点）跳转到离它最近的整数格点。下面我将展示这一功能。”于是屏幕上生成了三个红点，每个点都自动跳转到最近的整数格点。“接下来我会离开这个房间，你们可以相互交流一下对这个软件的看法，或者靠近看一下这个软件。但是请不要做任何修改，因为我还没保存这个文件。”</div>
<div></div>
<div>几分钟后Tess回到了房间里，人群凑了过来。其中的一个人走上前来说：“我想你不会介意的，我稍微动了一下软件。不过不用担心，我只是玩了玩x坐标和y坐标的缩放功能。”另一个人动了坐标平移功能，而第三个人使用了旋转功能。</div>
<div></div>
<div>使用旋转功能的人记得他是最早做改动的，然而剩下的两个人忘记了他们的修改顺序。这三个人对他们的改动只记得一点细节。修改时的缩放系数是非零整数（可能是负数）；坐标的平移量是整数；旋转操作是这样完成的：在以原点为中心，边长为20的正方形上任选一个整点，旋转坐标轴使x轴通过该点，并保持原先的单位长度不变。旋转之后，图上的所有点四舍五入跳转到了距离最近的整点。注意形如-n + 0.5 (n &gt; 0)的坐标跳转到了-n。</div>
<div></div>
<div>人群离开之后，Tess发现自己的图形已经面目全非。软件的撤销功能还没有实现，而且她之前没有做过任何保存。幸运的是，她仍记得开始时三个红点的坐标，并且可以读出它们现在的坐标。利用这些信息，请你推断出访客们做的修改操作。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据，每组数据包含六对整数，x_i, y_i (1 &lt;= i &lt;= 6)。前三对数描述了开始时红点所在的坐标，后三对数描述了最后红点所在的坐标。请注意后三对数的顺序是不确定的，亦即，(x_1, y_1)可能对迎着(x_4, y_4)或者(x_5, y_5)等等。</div>
<div>最后一组数据之后包含六个零作为结束。</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>对每组数据，输出其编号以及以下信息之一：</div>
<div>
<div>- &#34;equivalent solutions&#34; : 存在一组或多组操作序列，但对于任意图形，这些序列会将该图形变换到同一图形。</div>
<div>- &#34;inconsistent solutions&#34; : 存在多组操作序列，并存在一个图形，使之会被其中的某两个序列变换到不同的图形。</div>
<div>- &#34;no solution&#34; : 不存在任何操作序列。</div>
<div>合法的操作序列由三个操作旋转、缩放和平移（或旋转、平移和缩放）组成，满足题中所述的条件。</div>
<div>请参照样例输出的格式。</div>
</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 0 4 0 1 4<br/>
-2 -4 -1 3 3 -4<br/>
0 1 1 1 2 1<br/>
1 2 2 2 3 2<br/>
1 0 2 0 3 0<br/>
3 3 1 1 2 2<br/>
1 0 2 0 3 0<br/>
3 2 1 1 2 2<br/>
2 3 0 6 1 2<br/>
2 3 0 6 1 2<br/>
0 0 0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: equivalent solutions<br/>
Case 2: inconsistent solutions<br/>
Case 3: no solution<br/>
Case 4: inconsistent solutions<br/>
Case 5: equivalent solutions</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

