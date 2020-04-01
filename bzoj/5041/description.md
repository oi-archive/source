
# Description

<div class="content"><div>
<div>Background</div>
<div>椭圆是平面内到定点F1、F2的距离之和等于一个定值（大于|F1F2|）的动点P的轨迹，F1、F2称为椭圆的两个焦点</div>
<div>。以下内容均发生在二维平面。DescriptionLWD垂涎YSY星球很久了，他总是幻想着自己有一天能到YSY星球上去生</div>
<div>活。好心的ZWD决定帮他一个忙，用他的宇宙飞船把LWD送上YSY星球。因为ZWD的飞船不能飞得太远，所以飞船只能</div>
<div>绕两个定点作椭圆轨道的飞行。并且因为ZWD还有更重要的事情要做，所以只想沿着YSY星球表面高速掠过，然后把</div>
<div>LWD丢出去。理论上来说，ZWD飞船的椭圆轨道与YSY星球会有两个切点，如下图，有A，B两个切点，所以说ZWD可以</div>
<div>选择在到A点把LWD丢出去或者到B再丢。但是ZWD想让他的椭圆轨道想尽量小，所以他会选择A点。由于ZWD飞船的导</div>
<div>航系统被拿去送给ZWD工作过的飞船驾驶学校作纪念了，所以他想请你帮助他解决导航的问题。现在你知道椭圆轨</div>
<div>道的两个焦点和YSY星球的坐标和半径，请你粗略地告诉ZWD LWD会降落在何处。</div>
</div>
<div><img src="/source/bzoj/5041/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOS92djEuanBn.jpg" width="494" height="262" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行一个整数t，表示数据组数。对与每组数据：</div>
<div>第一行四个实数x1,y1,x2,y2，表示两焦点坐标。</div>
<div>第二行三个实数x0,y0,r，表示YSY星球(在二维平面中是一个圆)的圆心坐标和半径。</div>
<div>t&lt;=500,x,y&lt;=1500,r&lt;=250；</div>
<div>保证一定存在两个可能的切点，即两焦点构成的线段不会与给出的圆相交。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出共t行，每行两个整数x,y，表示降落点的坐标。</div>
<div>误差不得超过 0.1（本题设置SPJ）</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
671.96 709.16 631.66 143.33<br/>
193.97 46.03 9.45<br/>
260.12 443.55 414.69 159.44<br/>
867.06 413.22 145.39<br/>
661.12 270.16 199.50 762.11<br/>
217.73 88.88 143.38<br/>
393.83 682.29 788.82 425.07<br/>
181.08 239.07 104.56<br/>
146.23 889.95 599.49 296.45<br/>
341.26 157.41 26.60</span></div>

# Sample Output

<div class="content"><span class="sampledata">201.87 51.22<br/>
725.78 378.91<br/>
299.74 206.49<br/>
259.56 308.16<br/>
352.26 181.63</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By onepointo">By onepointo</a></p></div>

