
# Description

<div class="content"><p><span style="font-size: medium">Over the years, FJ has made a huge number of farmer friends all around the world. Since he hasn&#39;t visited &#39;Farmer Ted&#39; from England and &#39;Boer Harms&#39; from Holland for a while, he&#39;d like to visit them. He knows the longitude of the farm where each of his worldwide friends resides. This longitude is an angle (an integer in the range 0..359) describing the farm&#39;s location on the Earth, which we will consider to be a circle instead of the more complex and traditional spherical representation. Except for the obvious discontinuity, longitudes increase when traveling clockwise on this circle. FJ plans to travel by airplane to visit his N (1 &lt;= N &lt;= 5,000) friends (whose farms are uniquely numbered 1..N). He knows the schedules for M (1 &lt;= M &lt;= 25,000) bidirectional flights connecting the different farms. Airplanes always travel shortest paths on the Earth&#39;s surface (i.e., on the shortest arc of a circle). There will always be a unique shortest path between two farms that are directly connected. No pair of antipodal farms (exactly opposite each other on the circle) is ever directly connected. Each airplane flight can be described as traveling in clockwise or counterclockwise direction around the Earth&#39;s surface. For example, a flight from longitude 30 to longitude 35 would be clockwise, as would be a flight from longitude 350 to longitude 10. However, a flight from longitude 350 to longitude 200 follows a shortest path counterclockwise around the circle. FJ would find it very cool if he could make a trip around the world, visiting some of his friends along the way. He&#39;d like to know if this is possible and if so, what is the minimum number of flights he can take to do so. He wants to start and finish his journey at the location of his best friend (the one listed first in the input below). In order to make sure he actually circles the Earth, he wants to ensure that the clockwise distance he travels is different from the counterclockwise distance he travels. </span></p>
<div><span style="font-size: medium">  这些年，农夫约翰在国际上交了一大批开农场的朋友．由于他有一段时间没有去见过英国的农夫泰德和荷兰的农夫波尔，所以他想去访问他们, 他知道每个朋友的农场的经度．经度（从0到359）是一种角度描述农场在地球上位置的方法，我们把地球看成一个圆，正如我们所熟知的，经度在地球上沿着顺时针方向增长, 农夫约翰打算乘飞机去访问他的N(1≤N≤5000)个朋友（用1到N来表示）．他知道在这些农场之间有M(1≤M≤25000)条双向的航线，当然飞机总是沿着地面上最短的路径飞行的（就是圆上的最短弧长）．两个农场之间的航线一定是最短的，也就是说如果育两个农场在直径两端，那么他们之间一定不存在航线．所以任何一次航行都可以被描述成顺时针或是逆时针的．比如说，经度30到经度35是顺时针的，经度350到经度10也是顺时针的，而经度350到经度200是逆时针的．</span></div>
<div><span style="font-size: medium">    农夫约翰为了耍酷，决定要经过几个朋友的农场做到环球旅行，他想知道这是否可能，如果可能最少要乘几次飞机．    他想在他最好的朋友（也就是列表中的第一个）的农场上开始和完成这次旅行．为了保证这是一次环球航行，回到终点时，顺时针经过的路程不能等于逆时针经过的路程．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: N and M * Lines 2..N+1: Line i+1 contains one integer: the longitude of the i-th farm. Line 2 contains the location of the farm of his best friend. * Lines N+2..N+M+1: Line i+N+1 contains two integers giving the indices of two farms that are connected by a flight.</span></p>
<div><span style="font-size: medium">    第1行：两个用空格隔开的整数N和M.</span></div>
<div><span style="font-size: medium">    第2到N+1行：第i+l行有一个整数，表示第i个农场的经度．第2行是他的最好的朋友的地址．</span></div>
<div><span style="font-size: medium">    第N+2过程N+M+I行：第i+N+1行有两个整数，表示这两个农场之间有航线．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer specifying the minimum number of flights FJ needs to visit to make a trip around the world. Every time FJ moves from one farm to another counts as one flight. If it is impossible to make such a trip, output the integer -1.</span></p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">    一个整数即农夫约翰至少要乘几次飞机才能完成环球旅行．每次农夫约翰从一个农场前往另一个农场算作乘一次飞机．如果不可能做到环球旅行则输出-1.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
0<br/>
120<br/>
240<br/>
1 2<br/>
2 3<br/>
1 3<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Farmer John has three friends at longitudes 0, 120, and 240.  There are<br/>
three flights: 0&lt;-&gt;120, 120&lt;-&gt;240, and 0&lt;-&gt;240.  The journey must start and<br/>
finish at longitude 0.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
FJ must visit all 3 friends to make a full trip around the world.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

