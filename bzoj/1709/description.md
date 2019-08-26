
# Description

<div class="content"><p><span style="font-size: medium">奶牛们最近从著名的奶牛玩具制造商Tycow那里，买了一套仿真版彩弹游戏设备（类乎于真人版CS）。 Bessie把她们玩游戏草坪划成了N * N(1 &lt;= N&lt;= 100)单位的矩阵，同时列出了她的 K (1 &lt;= K &lt;= 100,000)个对手在草地上的位置。然后她拿着这张表来找你，希望你能帮她计算一个数据。 在这个游戏中，奶牛可以用一把弹珠枪向8个方向中的任意一个射出子弹。8个方向分别是：正北，正南，正东，正西，以及夹在这4个正方向之间的45°角:东北，东南，西北，西南方向。 Bessie望你告诉她，如果她想站在一个可以射到她的所有对手的格子上，那么她有多少种选择。当然，贝茜可以跟她的某一个对手站在同一个格子上，并且在这种情况下，你可以认为贝茜能射到跟她站在同一格子里的对手。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 2个用空格隔开的整数：N和K </span></p>
<p><span style="font-size: medium">* 第2..K+1行: 第i+1行用2个以空格隔开整数R_i和C_i，描述了第i头奶牛的位置，表示她站在第R_i行，第C_i列</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个整数，表示如果Bessie可以选择的格子的数目。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
2 1<br/>
2 3<br/>
4 1<br/>
<br/>
输入说明:<br/>
<br/>
牧场被划分成了4行4列。Bessie的站位必须保证她能射到站在(2,1)，(2,3)<br/>
<br/>
以及(4,1)的奶牛：<br/>
<br/>
          . . . .<br/>
          C . C .<br/>
          . . . .   &lt;--- 奶牛们的位置<br/>
          C . . .<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
输出说明:<br/>
<br/>
Bessie可以选择站在以下格子中的任意一个：(2,1)，(2,3)，(3,2)，(4,1)，<br/>
以及(4,3)。下右图中，Bessie与其他牛共同占有的格子被标记为&#39;*&#39;：<br/>
       . . . .           . . . .<br/>
       B . B .   ---\    * . * .<br/>
       . B . .   ---/    . B . .<br/>
       B . B .           * . B .</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

