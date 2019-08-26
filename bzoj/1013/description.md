
# Description

<div class="content"><p>　　有一个球形空间产生器能够在n维空间中产生一个坚硬的球体。现在，你被困在了这个n维球体中，你只知道球<br/>
面上n+1个点的坐标，你需要以最快的速度确定这个n维球体的球心坐标，以便于摧毁这个球形空间产生器。</p></div>

# Input

<div class="content"><p>　　第一行是一个整数n(1&lt;=N=10)。接下来的n+1行，每行有n个实数，表示球面上一点的n维坐标。每一个实数精确到小数点<br/>
后6位，且其绝对值都不超过20000。</p></div>

# Output

<div class="content"><p>　　有且只有一行，依次给出球心的n维坐标（n个实数），两个实数之间用一个空格隔开。每个实数精确到小数点<br/>
后3位。数据保证有解。你的答案必须和标准输出一模一样才能够得分。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
0.0 0.0<br/>
-1.0 1.0<br/>
1.0 0.0</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.500 1.500</span></div>

# Hint

<div class="content"><p></p><p>　　提示：给出两个定义：1、 球心：到球面上任意一点距离都相等的点。2、 距离：设两个n为空间上的点A, B<br/><br/>
的坐标为(a1, a2, …, an), (b1, b2, …, bn)，则AB的距离定义为：dist = sqrt( (a1-b1)^2 + (a2-b2)^2 + <br/><br/>
… + (an-bn)^2 )</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

