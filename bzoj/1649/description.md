
# Description

<div class="content"><p><span style="font-size: medium">The cows are building a roller coaster! They want your help to design as fun a roller coaster as possible, while keeping to the budget. The roller coaster will be built on a long linear stretch of land of length L (1 &lt;= L &lt;= 1,000). The roller coaster comprises a collection of some of the N (1 &lt;= N &lt;= 10,000) different interchangable components. Each component i has a fixed length Wi (1 &lt;= Wi &lt;= L). Due to varying terrain, each component i can be only built starting at location Xi (0 &lt;= Xi &lt;= L-Wi). The cows want to string together various roller coaster components starting at 0 and ending at L so that the end of each component (except the last) is the start of the next component. Each component i has a &#34;fun rating&#34; Fi (1 &lt;= Fi &lt;= 1,000,000) and a cost Ci (1 &lt;= Ci &lt;= 1000). The total fun of the roller coster is the sum of the fun from each component used; the total cost is likewise the sum of the costs of each component used. The cows&#39; total budget is B (1 &lt;= B &lt;= 1000). Help the cows determine the most fun roller coaster that they can build with their budget. </span></p>
<div><span style="font-size: medium">奶牛们正打算造一条过山车轨道．她们希望你帮忙，找出最有趣，但又符合预算的方案．  过山车的轨道由若干钢轨首尾相连，由x=0处一直延伸到X=L(1≤L≤1000)处．现有N(1≤N≤10000)根钢轨，每根钢轨的起点Xi(0≤Xi≤L- Wi)，长度wi(l≤Wi≤L)，有趣指数Fi(1≤Fi≤1000000)，成本Ci(l≤Ci≤1000)均己知．请确定一种最优方案，使得选用的钢轨的有趣指数之和最大，同时成本之和不超过B(1≤B≤1000)．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: L, N and B.</span></p>
<p><span style="font-size: medium"> * Lines 2..N+1: Line i+1 contains four space-separated integers, respectively: Xi, Wi, Fi, and Ci.</span></p>
<div><span style="font-size: medium">    第1行输入L，N，B，接下来N行，每行四个整数Xi，wi，Fi，Ci．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the maximum fun value that a roller-coaster can have while staying within the budget and meeting all the other constraints. If it is not possible to build a roller-coaster within budget, output -1. </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6 10<br/>
0 2 20 6<br/>
2 3 5 6<br/>
0 1 2 1<br/>
1 1 1 3<br/>
1 2 5 4<br/>
3 2 10 2<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
 选用第3条，第5条和第6条钢轨</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

