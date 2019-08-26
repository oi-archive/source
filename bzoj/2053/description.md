
# Description

<div class="content"><div>给出N，Range，Seed_0，按照Seed_{i+1} = (Seed_i * 16807) mod (2^31-1)以及Rand_i = (Seed_i mod (2 * Range)) – Range的规则，计算出Rand_1 到Rand_{3n} 。定义三维空间内的点P_k的坐标为（Rand_{3k-2}, Rand_{3k-1}, Rand_{3k}）{1≤k≤n}。求出所有点中两点间最小距离的平方以及有多少对点的距离等于最小距离。 2 ≤ N ≤ 150000，1 ≤ Range ≤ 10^6，1 ≤ Seed ≤ 10^3 </div>
<div>注意:如果有多个点重合，就当成一个点</div></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
100<br/>
1<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9163<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p>The three points are: (-93, -51, -27), (-42, 30, -28), and (44, -22, 23). The closest pair of points are the first and third, and the square of their distance is 9163. There is 1 pair of points with a squared distance of 9163.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

