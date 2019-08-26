
# Description

<div class="content"><p>TooDee是一块二维格子状的土地（就像著名的笛卡尔坐标系那样） ，在这里<br/>
生活着很多可爱的Dee。Dee是像蜜蜂一样的小动物，它们只在二维活动，而且<br/>
它们非常的文明开化。TooDee 的蜂窝和正常世界的蜂窝也是很不一样的，它们<br/>
是矩形的且它们的边平行于TooDee的地理坐标系，就是说矩形的边或者是东西<br/>
走向，或者是南北走向。 <br/>
因为 Dees 是很高级的生物，它们有很多固定的飞行轨道，这些轨道由一些<br/>
平行于坐标轴的线段组成，线段只会在经纬度都是整数的点相交。 Dee在TooDee<br/>
飞行时必须遵守以下规则（请记住TooDee中所有点的经纬度都是整数）： <br/>
1  如果当前在点(XS, YS)， 则下步只能飞到四个邻点  (XS, YS – 1), (XS, YS + 1),   <br/>
(XS – 1, YS ), (XS + 1, YS )； <br/>
2  不可以进入蜂巢； <br/>
3  只能在蜂巢的角或者边上改变飞行方向； <br/>
4  开始的时候可以向任何方向飞； <br/>
今晚是公共财政大臣Deeficer的女儿的生日，她想尽早回家，请帮她找到最<br/>
快的回家路径。假设她每秒可以飞行一个单位的距离。</p></div>

# Input

<div class="content"><p>每个测试点包含多组数据。 <br/>
输入的第一行包含一个整数T，表示测试数据的组数。接下来依次描述这T<br/>
组数据，相邻的两组之间使用一个空行分隔。测试数据不多于20组。 <br/>
对于每组数据，第一行包含4个整数 xs, ys, xt, yt，表示Deeficer 的办公室和<br/>
家的坐标分别为(xs, ys)和(xt, yt)。第二行包含一个整数n，表示蜂巢的个数。接下<br/>
来的n行描述所有的蜂巢，其中第 i行包含 4 个整数xi1,  yi1,  xi2,  yi2，表示第i个<br/>
蜂巢两个对角的坐标分别为(xi1, yi1)和(xi2, yi2)。 <br/>
任何两个蜂巢都不会相交，也不会接触（在角上也不会接触）。办公室和家<br/>
处在不同的位置。每个蜂巢的面积为正。</p></div>

# Output

<div class="content"><p>对于每一组数据，输出一个整数，表示Deeficer 最快回家的时间（单位为秒），<br/>
如果她无法按规则回家，则输出“No Path”。</p>
<p>对于100%的测试数据，1 ≤ n ≤ 1000，所有坐标都是不超过10^9<br/>
的整数；</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
 <br/>
1 7 7 8 <br/>
2 <br/>
2 5 3 8 <br/>
4 10 6 7 <br/>
 <br/>
2 1 5 4 <br/>
1 <br/>
3 1 4 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">9 <br/>
No Path <br/>
 </span></div>

# Hint

<div class="content"><p></p><p>数据为国际加国内综合版</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

