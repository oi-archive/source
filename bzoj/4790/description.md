
# Description

<div class="content"><div>Luka非常擅长解决汉诺塔问题，他发明了一种类似汉诺塔的使用盘子和柱子的游戏。这个游戏有n个不同大小的盘</div>
<div>子以及36根柱子。盘子按照大小从小到大依次被编号为1到n。柱子形成了6行6列的矩阵，从上到下每行依次被编号</div>
<div>为1到6，从左到右每列依次被编号为1到6。</div>
<div><img src="/source/bzoj/4790/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNC9waWMoMSkuanBn.jpg" width="411" height="94" alt=""/></div>
<div>游戏一开始，n个盘子都被堆叠在左上角坐标为(1,1)的柱子上。对于每一次操作，玩家可以选择一个柱子，取出最</div>
<div>顶上若干个盘子，然后选择右边或者下面的某个柱子，将取出的盘子全部堆叠在其顶上（不会翻转顺序）。游戏的</div>
<div>目标是把所有盘子都移动到(6,6)，且自底向上大小依次递减。</div>
<div>给定游戏的初始局面，请找到任意一组玩通关的方法。数据保证解必定存在。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=40000)，表示盘子的数目。</div>
<div>第二行包含n个正整数d_1,d_2,...,d_n(1&lt;=d_i&lt;=n)，自底向上表示(1,1)柱子上每个盘子的编号。</div>
<div>输入数据保证不存在两个盘子的编号相同。</div>
<div></div></div>

# Output

<div class="content"><div>输出m行，m表示你的解中游戏操作的次数。</div>
<div>其中第i行包含4个参数r_i,c_i,p_i,n_i，表示第i步操作</div>
<div>即你选择了(r_i,c_i)最上方的n_i(n_i&gt;=1)个盘子，然后往p_i方向移动。</div>
<div>如果向右移动，那么p_i为“R”（不含引号）；如果向下移动，那么p_i为“D”（不含引号）。</div>
<div>若有多组方案，输出任意一组。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 6 5 4 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1 D 6<br/>
2 1 D 6<br/>
3 1 D 6<br/>
4 1 D 6<br/>
5 1 D 6<br/>
6 1 R 6<br/>
6 2 R 6<br/>
6 3 R 6<br/>
6 4 R 6<br/>
6 5 R 5<br/>
6 5 R 1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

