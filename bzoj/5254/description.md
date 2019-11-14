
# Description

<div class="content"><div>泰迪每天都要通过一条路从家到学校，这条路的起点是泰迪家，终点则是学校。</div>
<div>这条路中间还有n个路口，从第i-1个路口走到第i个路口需要di秒，每个路口都有一个红绿灯。更具体的，绿灯持</div>
<div>续时间是g秒，红灯持续时间是r秒。每天从第0秒开始，所有灯都是绿灯，持续g秒之后变为红灯，再过r秒变成绿</div>
<div>灯，以此类推，并且同一时刻所有灯都是相同状态。当泰迪到达一个路口，若是绿灯则可直接通过，若是红灯则需</div>
<div>原地等待至绿灯。若到达某一路口时灯的状态正好发生改变，则视达到路口时灯的颜色为其改变后的颜色，例如第</div>
<div>g秒到达一个路口则视为遇到红灯。</div>
<div>现在泰迪预计了接下来q天从家出发的时间，第j天将会在第tj秒从家出发，他希望你告诉他每天到达学校的最早时</div>
<div>间。你可以假定一天内泰迪一定可以到达学校。</div></div>

# Input

<div class="content"><div>第一行三个正整数n,g,r表示路口数以及绿灯、红灯持续的时间。</div>
<div>第二行n+1个正整数di表示相邻路口间的通行时间</div>
<div>d1表示从起点到第一个路口所需的时间，dn+1表示第n个路口到终点的所需时间。</div>
<div>第三行一个正整数q表示询问天数。</div>
<div>第四行q个非负整数tj表示每天的出发时间</div>
<div>n, q ≤ 5 × 10^4 , 2 ≤ g, r ≤ 10^9 , di, tj ≤ 10^9</div></div>

# Output

<div class="content"><div>共q行，对于每次询问输出一行一个整数表示答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1 3 2<br/>
5 2<br/>
5<br/>
1 2 3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
9<br/>
12<br/>
12<br/>
12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By ExfJoe">By ExfJoe</a></p></div>

