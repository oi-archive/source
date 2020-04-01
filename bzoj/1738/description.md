
# Description

<div class="content"><p><span style="font-size: medium">FJ&#39;s cows really hate getting wet so much that the mere thought of getting caught in the rain makes them shake in their hooves. They have decided to put a rain siren on the farm to let them know when rain is approaching. They intend to create a rain evacuation plan so that all the cows can get to shelter before the rain begins. Weather forecasting is not always correct, though. In order to minimize false alarms, they want to sound the siren as late as possible while still giving enough time for all the cows to get to some shelter. The farm has F (1 &lt;= F &lt;= 200) fields on which the cows graze. A set of P (1 &lt;= P &lt;= 1500) paths connects them. The paths are wide, so that any number of cows can traverse a path in either direction. Some of the farm&#39;s fields have rain shelters under which the cows can shield themselves. These shelters are of limited size, so a single shelter might not be able to hold all the cows. Fields are small compared to the paths and require no time for cows to traverse. Compute the minimum amount of time before rain starts that the siren must be sounded so that every cow can get to some shelter. </span></p>
<div><span style="font-size: medium">    约翰的牛们非常害怕淋雨，那会使他们瑟瑟发抖．他们打算安装一个下雨报警器，并且安排了一个撤退计划．他们需要计算最少的让所有牛进入雨棚的时间．</span><span style="font-size: medium">    牛们在农场的F(1≤F≤200)个田地上吃草．有P(1≤P≤1500)条双向路连接着这些田地．</span><span style="font-size: medium">路很宽，无限量的牛可以通过．田地上有雨棚，雨棚有一定的容量，牛们可以瞬间从这块田地进入这块田地上的雨棚    请计算最少的时间，让每只牛都进入雨棚．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: F and P </span></p>
<p><span style="font-size: medium"> * Lines 2..F+1: Two space-separated integers that describe a field. The first integer (range: 0..1000) is the number of cows in that field. The second integer (range: 0..1000) is the number of cows the shelter in that field can hold. Line i+1 describes field i. * Lines F+2..F+P+1: Three space-separated integers that describe a path. The first and second integers (both range 1..F) tell the fields connected by the path. The third integer (range: 1..1,000,000,000) is how long any cow takes to traverse it. </span></p>
<div><span style="font-size: medium">    第1行：两个整数F和P;</span></div>
<div><span style="font-size: medium">    第2到F+1行：第i+l行有两个整数描述第i个田地，第一个表示田地上的牛数，第二个表示田地上的雨棚容量．两个整数都在0和1000之间．</span></div>
<div><span style="font-size: medium">    第F+2到F+P+I行：每行三个整数描述一条路，分别是起点终点，及通过这条路所需的时间（在1和10^9之间）．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The minimum amount of time required for all cows to get under a shelter, presuming they plan their routes optimally. If it not possible for the all the cows to get under a shelter, output &#34;-1&#34;. </span></p>
<div><span style="font-size: medium">    一个整数，表示最少的时间．如果无法使牛们全部进入雨棚，输出-1.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
7 2<br/>
0 4<br/>
2 6<br/>
1 2 40<br/>
3 2 70<br/>
2 3 90<br/>
1 3 120<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">110<br/>
<br/>
    1号田的7只牛中，2只牛直接进入1号田的雨棚，4只牛进入1号田的雨棚，1只进入3号田的雨棚，加入其他的由3号田来的牛们．所有的牛都能在110单位时间内到达要去的雨棚．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

