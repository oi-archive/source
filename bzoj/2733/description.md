
# Description

<div class="content"><p><span style="font-size: medium">永无乡包含 n 座岛，编号从 1 到 n，每座岛都有自己的独一无二的重要度，按照重要度可 以将这 n 座岛排名，名次用 1 到 n 来表示。某些岛之间由巨大的桥连接，通过桥可以从一个岛 到达另一个岛。如果从岛 a 出发经过若干座（含 0 座）桥可以到达岛 b，则称岛 a 和岛 b 是连 通的。现在有两种操作：B x y 表示在岛 x 与岛 y 之间修建一座新桥。Q x k 表示询问当前与岛 x连通的所有岛中第 k 重要的是哪座岛，即所有与岛 x 连通的岛中重要度排名第 k 小的岛是哪 座，请你输出那个岛的编号。 <br/>
 </span></p></div>

# Input

<div class="content"><p><font size="4">输入文件第一行是用空格隔开的两个正整数 n 和 m，分别 表示岛的个数以及一开始存在的桥数。接下来的一行是用空格隔开的 n 个数，依次描述从岛 1 到岛 n 的重要度排名。随后的 m 行每行是用空格隔开的两个正整数 ai 和 bi，表示一开始就存 在一座连接岛 ai 和岛 bi 的桥。后面剩下的部分描述操作，该部分的第一行是一个正整数 q， 表示一共有 q 个操作，接下来的 q 行依次描述每个操作，操作的格式如上所述，以大写字母 Q 或B 开始，后面跟两个不超过 n 的正整数，字母与数字以及两个数字之间用空格隔开。 对于 20%的数据 n≤1000,q≤1000 <br/>
 <br/>
对于 100%的数据 n≤100000,m≤n，q≤300000 <br/>
 <br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">对于每个 Q x k 操作都要依次输出一行，其中包含一个整数，表 示所询问岛屿的编号。如果该岛屿不存在，则输出-1。 <br/>
 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5  1           <br/>
4  3 2 5 1        <br/>
1  2           <br/>
7<br/>
Q 3 2           <br/>
Q 2 1 <br/>
B 2 3 <br/>
B 1 5 <br/>
Q 2 1 <br/>
Q 2 4 <br/>
Q 2 3 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">-1<br/>
2<br/>
5<br/>
1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

