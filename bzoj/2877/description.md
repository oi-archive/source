
# Description

<div class="content"></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行为两个正整数N,M，表示棋盘的大小。 第二行为两个正整数X,Y，表示棋盘守护者的位置。 第三行仅有一个正整数T，表示棋盘守护者将进行次操作。 接下来N行，每行有M个正整数，用来描述初始时棋盘上每个位置的数。 接下来T行，按操作的时间顺序给出T次操作。每行描述一次操作，以一个数字0或1开头： 若以数字0开头，表示此操作为询问，随后会有四个非负整数x1,y1,x2,y2，表示询问的区域是以棋盘守护者的位置为基础向上扩展x1行，向下扩展y1行，向左扩展x2列，向右扩展y2列得到的矩形区域（详见样例）。 若以数字1开头，表示此操作为修改，随后会有四个正整数x1,y1,x2,y2和一个整数c，表示修改区域的上、下边界分别为第x1,x2行，左、右边界分别为第y1,y2列（详见样例），在此矩形区域内的所有数统一加上c（注意c可能为负数）。<br/>
</span></p></div>

# Output

<div class="content"><p><br/>
<font size="4"> 对于每次询问操作，每行输出一个数，表示该区域内所有数的最大公约数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
1 1 <br/>
4 <br/>
6 12 <br/>
18 24<br/>
0 0 0 1 0 <br/>
1 1 1 1 2 6<br/>
1 2 1 2 2 6<br/>
0 0 0 1 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

