<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　最近房地产商GDOI(Group of Dumbbells Or Idiots)从NOI(Nuts Old Idiots)手中得到了一块开发土地。据了解，这块土地是一块矩形的区域，可以纵横划分为N×M块小区域。GDOI要求将这些区域分为商业区和工业区来开发。根据不同的地形环境，每块小区域建造商业区和工业区能取得不同的经济价值。更具体点，对于第i行第j列的区域，建造商业区将得到Aij收益，建造工业区将得到Bij收益。另外不同的区域连在一起可以得到额外的收益，即如果区域(I,j)相邻（相邻是指两个格子有公共边）有K块（显然K不超过4）类型不同于(I,j)的区域，则这块区域能增加k×Cij收益。经过Tiger.S教授的勘察，收益矩阵A,B,C都已经知道了。你能帮GDOI求出一个收益最大的方案么？</div>
# 输入格式

<div class="pdcont">　　输入第一行为两个整数，分别为正整数N和M，分别表示区域的行数和列数；<br/>
　　第2到N+1列，每行M个整数，表示商业区收益矩阵A；<br/>
　　第N+2到2N+1列，每行M个整数，表示工业区收益矩阵B；<br/>
　　第2N+2到3N+1行，每行M个整数，表示相邻额外收益矩阵C。第一行，两个整数，分别是n和m（1≤n，m≤100）；</div>
# 输出格式

<div class="pdcont">　　输出只有一行，包含一个整数，为最大收益值。</div>
# 样例输入

<div class="pddata">3 3<br/>
1 2 3<br/>
4 5 6<br/>
7 8 9<br/>
9 8 7<br/>
6 5 4<br/>
3 2 1<br/>
1 1 1<br/>
1 3 1<br/>
1 1 1</div>
# 样例输出

<div class="pddata">81</div>
# 数据规模和约定

<div class="pdcont">　　N,M≤100,0≤Aij,Bij,Cik≤1000<br/>
　　对于30%的数据有N,M≤6<br/>
　　对于50%的数据有N,M≤20<br/>
　　对于100%的数据有N,M≤100</div>

</div>