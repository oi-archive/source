
# Description

<div class="content"><p><span style="font-size: medium">清早6：00，Farmer John就离开了他的屋子，开始了他的例行工作：为贝茜挤奶。前一天晚上，整个农场刚经受过一场瓢泼大雨的洗礼，于是不难想见，FJ 现在面对的是一大片泥泞的土地。FJ的屋子在平面坐标(0, 0)的位置，贝茜所在的牛棚则位于坐标(X,Y) (-500 &lt;= X &lt;= 500; -500 &lt;= Y &lt;= 500)处。当然咯， FJ也看到了地上的所有N(1 &lt;= N &lt;= 10,000)个泥塘，第i个泥塘的坐标为 (A_i, B_i) (-500 &lt;= A_i &lt;= 500；-500 &lt;= B_i &lt;= 500)。每个泥塘都只占据了它所在的那个格子。 Farmer John自然不愿意弄脏他新买的靴子，但他同时想尽快到达贝茜所在的位置。为了数那些讨厌的泥塘，他已经耽搁了一些时间了。如果Farmer John 只能平行于坐标轴移动，并且只在x、y均为整数的坐标处转弯，那么他从屋子门口出发，最少要走多少路才能到贝茜所在的牛棚呢？你可以认为从FJ的屋子到牛棚总是存在至少一条不经过任何泥塘的路径。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 3个用空格隔开的整数：X，Y 和 N </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1行为2个用空格隔开的整数：A_i 和 B_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个整数，即FJ在不踏进泥塘的情况下，到达贝茜所在牛棚所需要 走过的最小距离 </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2 7<br/>
0 2<br/>
-1 3<br/>
3 1<br/>
1 1<br/>
4 2<br/>
-1 1<br/>
2 2<br/>
<br/>
输入说明:<br/>
<br/>
    贝茜所在牛棚的坐标为(1, 2)。Farmer John能看到7个泥塘，它们的坐标分<br/>
别为(0, 2)、(-1, 3)、(3, 1)、(1, 1)、(4, 2)、(-1, 1)以及(2, 2)。<br/>
    以下为农场的简图：（*为FJ的屋子，B为贝茜呆的牛棚）<br/>
<br/>
   4 . . . . . . . . <br/>
   3 . M . . . . . . <br/>
Y  2 . . M B M . M . <br/>
   1 . M . M . M . . <br/>
   0 . . * . . . . . <br/>
  -1 . . . . . . . . <br/>
    -2-1 0 1 2 3 4 5 <br/>
<br/>
           X<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium">    约翰的最佳路线是：(0，0)，（一1，0），（一2，0），（一2，1），（一2，2），（一2，3），（一2，4），（一1，4），(0,4),  (0,3),  (1,3),  (1,2).</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

