
# Description

<div class="content"><p>(buying.pas/buying.in/buying.out 128M 1S) Farmer John needs to travel to town to pick up K (1 &lt;= K &lt;= 100) pounds of feed. Driving D miles with K pounds of feed in his truck costs D*K cents. The county feed lot has N (1 &lt;= N &lt;= 100) stores (conveniently numbered 1..N) that sell feed. Each store is located on a segment of the X axis whose length is E (1 &lt;= E &lt;= 350). Store i is at location X_i (0 &lt; X_i &lt; E) on the number line and can sell FJ as much as F_i (1 &lt;= F_i &lt;= 100) pounds of feed at a cost of C_i (1 &lt;= C_i &lt;= 1,000,000) cents per pound. Amazingly, a given point on the X axis might have more than one store.  FJ starts at location 0 on this number line and can drive only in the positive direction, ultimately arriving at location E, with at least K pounds of feed. He can stop at any of the feed stores along the way and buy any amount of feed up to the the store&#39;s limit.  What is the minimum amount FJ has to pay to buy and transport the K pounds of feed? FJ knows there is a solution.  Consider a sample where FJ needs two pounds of feed from three stores (locations: 1, 3, and 4) on a number line whose range is 0..5:        0   1   2   3   4   5       +---|---+---|---|---+           1       1   1      Available pounds of feed           1       2   2      Cents per pound  It is best for FJ to buy one pound of feed from both the second and third stores. He must pay two cents to buy each pound of feed for a total cost of 4. When FJ travels from 3 to 4 he is moving 1 unit of length and he has 1 pound of feed so he must pay 1*1 = 1 cents.  When FJ travels from 4 to 5 he is moving one unit and he has 2 pounds of feed so he must pay 1*2 = 2 cents.  The total cost is 4+1+2 = 7 cents.</p>
<p>FJ开车去买K份食物，如果他的车上有X份食物。每走一里就花费X元。 FJ的城市是一条线，总共E里路，有E+1个地方，标号0~E。 FJ从0开始走，到E结束（不能往回走），要买K份食物。 城里有N个商店，每个商店的位置是X_i（一个点上可能有多个商店），有F_i份食物，每份C_i元。 问到达E并买K份食物的最小花费</p></div>

# Input

<div class="content"><p>第1行：K,E,N 第2~N+1行：X_i,F_i,C_i.</p></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">2 5 3<br/>
3 1 2<br/>
4 1 2<br/>
1 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
</span></div>

# Hint

<div class="content"><p></p><p>在离家较近的两家商店里各购买一吨饲料，<br/><br/>
则花在路上的钱是 1 + 2 = 3，花在店里的钱是2 + 2 = 4</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

