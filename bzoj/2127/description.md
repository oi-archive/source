
# Description

<div class="content"><p>高一一班的座位表是个n*m的矩阵，经过一个学期的相处，每个同学和前后左右相邻的同学互相成为了好朋友。这学期要分文理科了，每个同学对于选择文科与理科有着自己的喜悦值，而一对好朋友如果能同时选文科或者理科，那么他们又将收获一些喜悦值。作为计算机竞赛教练的scp大老板，想知道如何分配可以使得全班的喜悦值总和最大。</p></div>

# Input

<div class="content"><p>第一行两个正整数n，m。接下来是六个矩阵第一个矩阵为n行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学选择文科获得的喜悦值。第二个矩阵为n行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学选择理科获得的喜悦值。第三个矩阵为n-1行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i+1行第j列的同学同时选择文科获得的额外喜悦值。第四个矩阵为n-1行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i+1行第j列的同学同时选择理科获得的额外喜悦值。第五个矩阵为n行m-1列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i行第j+1列的同学同时选择文科获得的额外喜悦值。第六个矩阵为n行m-1列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i行第j+1列的同学同时选择理科获得的额外喜悦值。</p></div>

# Output

<div class="content"><p>输出一个整数，表示喜悦值总和的最大值</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
1 1<br/>
100 110<br/>
1<br/>
1000 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1210<br/>
【样例说明】<br/>
两人都选理，则获得100+110+1000的喜悦值。<br/>
【数据规模】<br/>
对于100%以内的数据，n,m&lt;=100  所有喜悦值均为小于等于5000的非负整数<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

