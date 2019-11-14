
# Description

<div class="content"><div>这是2112年，人类已经征服了太阳系。太空游侠队已经在任何大块岩石上建立了基地（即使不适宜居住）。你作为小行星通讯部门的一员，工作是确保所有太空游侠小行星基地都能尽可能廉价地与其他小行星基地交流。你可以建立从每个基地到另外所有基地的直接交流连接，但那可能过分昂贵。相反，你想要建立最少数量的连接从而每个人都可以发送信息给其他所有人，信息可能通过一个或多个基地中转。建立任何连接的费用与它连接的两个基地之间的（欧几里德）距离成比例，所以这个问题看起来不怎么难。</div>
<div>但这只是一个小小的困难。小行星有一个运动的趋势，所以两个当前很接近的基地在将来不一定还是很接近。因此随着时间流逝，你一定会乐意转换你的交流连接，从而在任何时候你都拥有最廉价的中继系统。转换这些连接花费时间和金钱，所以你对于了解将要执行多少次转换很感兴趣。</div>
<div>一些假设让这个任务更简单。每个小行星可以视为一个点。小行星总是以固定的速度沿直线运动。没有小行星会和其他小行星相撞。此外，任何在时刻t(t≥0)变得最优的中继系统在任何时刻s(s满足t&lt;s&lt;t+10^-6)时是独一无二最优的。初始最优的中继系统也是独一无二的。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>每组数据（tsinsen上的数据均为单组数据）以包含一个整数n的一行开始，其中n表示小行星基地的数量。</div>
<div>接下来n行，每行包含6个整数x,y,z,vx,vy,vz，前三个表示这个小行星的初始位置，后三个表示小行星在x,y,z三维上的速度（单位空间每单位时间）。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出一行，包含数据编号和中继系统需要被建立或修改的次数。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 0 0 0 0 0<br/>
5 0 0 0 0 0<br/>
10 1 0 -1 0 0<br/>
4<br/>
0 0 0 1 0 0<br/>
0 1 0 0 -1 0<br/>
1 1 1 3 1 1<br/>
-1 -1 2 1 -1 -1</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 3<br/>
Case 2: 3</span></div>

# Hint

<div class="content"><p></p><p>100%的数据满足n≤50,-150≤x,y,z≤150,-100≤vx,vy,vz≤100。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

