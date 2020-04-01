
# Description

<div class="content"><div>给定N个同心的扇形，求有多少面积，被至少K个扇形所覆盖。</div>
<p></p></div>

# Input

<div class="content"><div>第一行是三个整数n，m，k。n代表同心扇形的个数，m用来等分 [-π,π]的弧度。</div>
<div>从第二行开始的n行，每行三个整数r，a1，a2。描述了一个圆心在原点的扇形，半径为r，圆心角是从弧度πa1/m到πa2/m，a1可能大于a2，逆时针扫过的区域为该扇形面积。</div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数ans，至少被K个扇形所覆盖的总面积等于π/2m×ans</div>
<div>保证答案不超过2^63-1</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
3 8 2<br/>
1 -8 8<br/>
3 -7 3<br/>
5 -5 5<br/>
【输入样例2】<br/>
2 4 1<br/>
4 4 2<br/>
1 -4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例1】<br/>
76<br/>
【输出样例2】<br/>
98<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1≤n≤10^5,   1≤m≤10^6,1≤k≤5000,1≤ri≤10^5,-m≤a1,a2≤m</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

