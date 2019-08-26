
# Description

<div class="content"><div>最近房地产商GDOI(Group of Dumbbells Or Idiots)从NOI(Nuts Old Idiots)手中得到了一块开发土地。据了解，</div>
<div>这块土地是一块矩形的区域，可以纵横划分为N×M块小区域。GDOI要求将这些区域分为商业区和工业区来开发。根</div>
<div>据不同的地形环境，每块小区域建造商业区和工业区能取得不同的经济价值。更具体点，对于第i行第j列的区域，</div>
<div>建造商业区将得到Aij收益，建造工业区将得到Bij收益。另外不同的区域连在一起可以得到额外的收益，即如果区</div>
<div>域(I,j)相邻（相邻是指两个格子有公共边）有K块（显然K不超过4）类型不同于(I,j)的区域，则这块区域能增加k</div>
<div>×Cij收益。经过Tiger.S教授的勘察，收益矩阵A,B,C都已经知道了。你能帮GDOI求出一个收益最大的方案么？</div></div>

# Input

<div class="content"><div>输入第一行为两个整数，分别为正整数N和M，分别表示区域的行数和列数；</div>
<div>第2到N+1列，每行M个整数，表示商业区收益矩阵A；</div>
<div>第N+2到2N+1列，每行M个整数，表示工业区收益矩阵B；</div>
<div>第2N+2到3N+1行，每行M个整数，表示相邻额外收益矩阵C。</div>
<div>任何数字不超过1000”的限制</div></div>

# Output

<div class="content"><p>输出只有一行，包含一个整数，为最大收益值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 3<br/>
4 5 6<br/>
7 8 9<br/>
9 8 7<br/>
6 5 4<br/>
3 2 1<br/>
1 1 1<br/>
1 3 1<br/>
1 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">81<br/>
【数据规模】<br/>
对于100%的数据有N,M≤100<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 数据已加强，并重测--2015.5.15</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

