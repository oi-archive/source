
# Description

<div class="content"><div>你需要实现以下3种操作：</div>
<div>1.       平面上加入一条直线；</div>
<div>2.       删除一条已加入的直线；</div>
<div>3.       求一个点到平面上所有直线距离平方和最小，你需要输出这个最小值。</div>
<div></div>
<div>
<p></p>
</div></div>

# Input

<div class="content"><div>第1行包含一个整数N，表示了操作数目。接下来N行操作属于下列3种格式之一：</div>
<div>格式1: 0 x1 y1 x2 y2 。插入直线操作，插入一条过(x1, y1), (x2, y2)的直线，保证两点不重合，坐标为实数（最多两位小数）并且绝对值不超过100。</div>
<div>格式2: 1 k 。删除直线操作，删除第i次插入操作所插入的直线，保证已经被删除的直线不会再被删除（即任意2次操作k值均不同），并且k不大于之前插入操作的次数。</div>
<div>格式3: 2 。查询操作，查询所要求的最小值。</div></div>

# Output

<div class="content"><p>输出行数等于查询操作的次数，每行输出每次查询操作所要求的最小值，保留两位小数</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
0 0.0 0.0 1.0 0.0<br/>
2<br/>
0 0 1 1 1<br/>
2<br/>
0 0 2 1 2<br/>
2<br/>
1 2<br/>
2<br/>
1 3<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.00<br/>
0.50<br/>
2.00<br/>
2.00<br/>
0.00<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N ≤ 120000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

