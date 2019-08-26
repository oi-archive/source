
# Description

<div class="content"><div><span style="font-size: medium">    约翰在加勒比海买下地产，准备在这里的若干个岛屿上养奶牛．所以，他要给所有岛屿围上篱笆．每个岛屿都是多边形．他沿着岛屿的一条边界朝一个方向走，有时候坐船到另一个岛去．他可以从任意一个多边形顶点开始修篱笆的工作；在任意一个到达的顶点，他可以坐船去另一个岛屿的某个顶点，但修完那个岛的篱笆，他必须马上原路返回这个出发的岛屿顶点．任意两个顶点间都有肮线，每条航线都需要一定的费用．请帮约翰计算最少的费用，让他修完所有篱笆．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入N(3≤N≤500)，表示所有岛屿多边形的个数．</span></div>
<div><span style="font-size: medium">    接下来N行每行输入两个整数V1和V2(1≤V1≤N;1≤V2≤N)，表示一条构成岛屿的线段的两个端点．</span><span style="font-size: medium">接下来输入N行N列的矩阵，表示两个顶点间航行所需费用．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    一个整数，最少费用．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">12<br/>
1 7<br/>
7 3<br/>
3 6<br/>
6 10<br/>
10 1<br/>
2 12<br/>
2 9<br/>
8 9<br/>
8 12<br/>
11 5<br/>
5 4<br/>
11 4<br/>
0 15 9 20 25 8 10 13 17 8 8 7<br/>
15 0 12 12 10 10 8 15 15 8 8 9<br/>
9 12 0 25 20 18 16 14 13 7 12 12<br/>
20 12 25 0 8 13 14 15 15 10 10 10<br/>
25 10 20 8 0 16 20 18 17 18 9 11<br/>
8 10 18 13 16 0 10 9 11 10 8 12<br/>
10 8 16 14 20 10 0 18 20 6 16 15<br/>
13 15 14 15 18 9 18 0 5 12 12 13<br/>
17 15 13 15 17 11 20 5 0 22 8 10<br/>
8 8 7 10 18 10 6 12 22 0 11 12<br/>
8 8 12 10 9 8 16 12 8 11 0 9<br/>
7 9 12 10 11 12 15 13 10 12 9 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">30</span></div>

# Hint

<div class="content"><p></p><p><img height="472" width="817" alt="" src="source/bzoj/3397/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS9hZmYoMikuanBn.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

