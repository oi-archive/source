
# Description

<div class="content"><div>一家餐厅有 n 道菜，编号 1...n ，大家对第 i 道菜的评价值为 ai(1≤i≤n)。有 m 位顾客，第 i 位顾客的期</div>
<div>望值为 bi，而他的偏好值为 xi 。因此，第 i 位顾客认为第 j 道菜的美味度为 bi XOR (aj+xi)，XOR 表示异或</div>
<div>运算。第 i 位顾客希望从这些菜中挑出他认为最美味的菜，即美味值最大的菜，但由于价格等因素，他只能从第 </div>
<div>li 道到第 ri 道中选择。请你帮助他们找出最美味的菜。</div>
<div></div></div>

# Input

<div class="content"><div>第1行，两个整数，n，m，表示菜品数和顾客数。</div>
<div>第2行，n个整数，a1，a2，...，an，表示每道菜的评价值。</div>
<div>第3至m+2行，每行4个整数，b，x，l，r，表示该位顾客的期望值，偏好值，和可以选择菜品区间。</div>
<div>1≤n≤2×10^5，0≤ai,bi,xi＜10^5，1≤li≤ri≤n(1≤i≤m)；1≤m≤10^5</div>
<div></div></div>

# Output

<div class="content"><p> 输出 m 行，每行 1 个整数，ymax ，表示该位顾客选择的最美味的菜的美味值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 <br/>
1 2 3 4 <br/>
1 4 1 4 <br/>
2 3 2 3 <br/>
3 2 3 3 <br/>
4 1 2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">9 <br/>
7 <br/>
6 <br/>
7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

