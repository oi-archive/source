
# Description

<div class="content"><p><span style="font-size: medium">N个点，形成一个树状结构。有M次发放，每次选择两个点x,y<br/>
对于x到y的路径上（含x,y)每个点发一袋Z类型的物品。完成<br/>
所有发放后，每个点存放最多的是哪种物品。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行数字N，M<br/>
接下来N-1行，每行两个数字a,b,表示a与b间有一条边<br/>
再接下来M行，每行三个数字x,y,z.如题</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
</span></p>
<p><span style="font-size: medium">输出有N行<br/>
每i行的数字表示第i个点存放最多的物品是哪一种，如果有<br/>
多种物品的数量一样，输出编号最小的。如果某个点没有物品<br/>
则输出0</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">20 50<br/>
8 6<br/>
10 6<br/>
18 6<br/>
20 10<br/>
7 20<br/>
2 18<br/>
19 8<br/>
1 6<br/>
14 20<br/>
16 10<br/>
13 19<br/>
3 14<br/>
17 18<br/>
11 19<br/>
4 11<br/>
15 14<br/>
5 18<br/>
9 10<br/>
12 15<br/>
11 14 87<br/>
12 1 87<br/>
14 3 84<br/>
17 2 36<br/>
6 5 93<br/>
17 6 87<br/>
10 14 93<br/>
5 16 78<br/>
6 15 93<br/>
15 5 16<br/>
11 8 50<br/>
17 19 50<br/>
5 4 87<br/>
15 20 78<br/>
1 17 50<br/>
20 13 87<br/>
7 15 22<br/>
16 11 94<br/>
19 8 87<br/>
18 3 93<br/>
13 13 87<br/>
2 1 87<br/>
2 6 22<br/>
5 20 84<br/>
10 12 93<br/>
18 12 87<br/>
16 10 93<br/>
8 17 93<br/>
14 7 36<br/>
7 4 22<br/>
5 9 87<br/>
13 10 16<br/>
20 11 50<br/>
9 16 84<br/>
10 17 16<br/>
19 6 87<br/>
12 2 36<br/>
20 9 94<br/>
9 2 84<br/>
14 1 94<br/>
5 5 94<br/>
8 17 16<br/>
12 8 36<br/>
20 17 78<br/>
12 18 50<br/>
16 8 94<br/>
2 19 36<br/>
10 18 36<br/>
14 19 50<br/>
4 12 50<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">87<br/>
36<br/>
84<br/>
22<br/>
87<br/>
87<br/>
22<br/>
50<br/>
84<br/>
87<br/>
50<br/>
36<br/>
87<br/>
93<br/>
36<br/>
94<br/>
16<br/>
87<br/>
50<br/>
50<br/>
<br/>
<br/>
<br/>
1&lt;=N,M&lt;=100000<br/>
1&lt;=a,b,x,y&lt;=N<br/>
1&lt;=z&lt;=10^9<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

