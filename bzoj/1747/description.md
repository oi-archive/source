
# Description

<div class="content"><p><span style="font-size: medium">A group of cows grabbed a truck and ventured on an expedition deep into the jungle. Being rather poor drivers, the cows unfortunately managed to run over a rock and puncture the truck&#39;s fuel tank. The truck now leaks one unit of fuel every unit of distance it travels. To repair the truck, the cows need to drive to the nearest town (no more than 1,000,000 units distant) down a long, winding road. On this road, between the town and the current location of the truck, there are N (1 &lt;= N &lt;= 10,000) fuel stops where the cows can stop to acquire additional fuel (1..100 units at each stop). The jungle is a dangerous place for humans and is especially dangerous for cows. Therefore, the cows want to make the minimum possible number of stops for fuel on the way to the town. Fortunately, the capacity of the fuel tank on their truck is so large that there is effectively no limit to the amount of fuel it can hold. The truck is currently L units away from the town and has P units of fuel (1 &lt;= P &lt;= 1,000,000). Determine the minimum number of stops needed to reach the town, or if the cows cannot reach the town at all. </span></p>
<div><span style="font-size: medium">    一群奶牛抢了一辆卡车决定前往树林里探险．但是由于它们的驾驶技术太糟，油箱在路上给弄破了，所以它们每前进一个单位的路程就会漏掉一个单位的油,为了修好油箱，奶牛们必须前往最近的城市（不会超过1000000单位路程）．在当前位置和城市之间有N(1≤N≤10000)个加油站．奶牛可以在加油站加1到100单位的油．对于人来说，树林是个危险的地方，对奶牛来说，更是这样．所以，奶牛要尽可能的少停站加油．幸运的是，这辆卡车的油箱非常大，你可以认为它的容量是无穷大的．卡车在离城P(1≤P≤1000000)个单位时还有L个单位的油． 你要算出奶牛们至少要停几站才能到城市，或者奶牛们根本到不了城市．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, N * Lines 2..N+1: Each line contains two space-separated integers describing a fuel stop: The first integer is the distance from the town to the stop; the second is the amount of fuel available at that stop. * Line N+2: Two space-separated integers, L and P </span></p>
<div><span style="font-size: medium">    第1行：一个整数N.</span></div>
<div><span style="font-size: medium">    第2到N+1行：每行有两个用空格隔开的整数，描述一个加油站．第一个数表示这个加油站离城市的距离，第二个数表示在这个加油站最多可以加多少油．</span></div>
<div><span style="font-size: medium">    第N+1行：两个用空格分开的整数L和P．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer giving the minimum number of fuel stops necessary to reach the town. If it is not possible to reach the town, output -1. </span></p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">    一个表示卡车到城市最少要停的次数，如果无法到达输出-1.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 4<br/>
5 2<br/>
11 5<br/>
15 10<br/>
25 10<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The truck is 25 units away from the town; the truck has 10 units<br/>
of fuel.  Along the road, there are 4 fuel stops at distances 4,<br/>
5, 11, and 15 from the town (so these are initially at distances<br/>
21, 20, 14, and 10 from the truck).  These fuel stops can supply<br/>
up to 4, 2, 5, and 10 units of fuel, respectively.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
现在卡车离城市25个单位，卡车里有10个单位的油．在路上，有4个加油站，分别距离城市4，5，11，15，分别距离卡车则为21，20，14，10.这些加油站分别最多可加油4，2，5，10个单位．开10个单位，加满油10单位油，在开4个单位，加满5单位的油，接着直接开到城市<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

