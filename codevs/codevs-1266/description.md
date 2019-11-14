<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>When she is bored, Jo Coder likes to play the following game with coins on a table.</p>
<p>当习core无聊的时候，李core会和他一起在桌子上玩下面的这个硬币游戏。</p>
<p>She takes a set of distinct coins and lines them up in a row.</p>
<p>习core把一堆不同面值的硬币排成一行。</p>
<p>For example, let us say that she has a penny (P, worth $0.01), a nickel (N, worth $0.05), and a dime (D, worth $0.10).</p>
<p>比如，如果说习core有一个1分，5分和1毛的硬币（分别用P,N,D代表）。</p>
<p>She lines them up in an arbitrary order, (for example, D N P), and then moves them around with the goal of placing them in strictly increasing order by value, that is P N D (i.e., $0.01, $0.05, $0.10). She has particular rules that she follows:</p>
<p>习core把他们排成DNP，然后目标是要通过下面的这些移动规则，他们移动成为按照面值升序的排列PND。</p>
<p><br>• The initial coin line-up deﬁnes all positions where coins can be placed. That is, no additional positions can be added later, and even if one of the positions does not have a coin on it at some point, the position still exists.</p>
<p>初始的位置定义了所有能够摆放硬币的位置，即使在中间某个时刻，某个位置上不存在硬币，这个位置也是存在的。</p>
<p>• The game consists of a sequence of moves and in each move Jo moves a coin from one position to an adjacent position.</p>
<p>这个游戏包含了一系列的移动，每一次移动，李core需要把一枚硬币从一个位置移动到相邻的一个位置中。</p>
<p>• The coins can be stacked, and in a move Jo always takes the top coin from one stack and moves it to the top of another stack.</p>
<p>硬币可以摞起来，在每次移动中，李core相当于要从一堆硬币的上面拿走一枚硬币放在另外一堆硬币的最上面。</p>
<p>• In a stack of coins, Jo never places a higher-value coin on top of a lower-value coin.</p>
<p>在移动的过程中，李core不能把面值高的硬币放在面值低的硬币的上面。</p>
<p>For simplicity, let the coins have consecutive integer values (e.g., denote the penny as 1, nickel as 2, and dime as 3). Then, in the above example, Jo could play the game in the following way in 20 moves (where XY denotes that coin X is on top of coin Y):</p>
<p>简单的说，用连续的整数代表硬币，比如1分用1，5分用2，1毛用3。然后，李core可以用如下的20步移动来玩这个游戏。（XY代表X放在Y的上面）</p>
<p><span style="">//这不是个表格，凑活着吧。</span></p>
<table border="0">
<tbody>
<tr>
<td>移动</td>
<td>位置1</td>
<td>位置2</td>
<td>位置3</td>
</tr>
<tr>
<td>初始状态</td>
<td>3</td>
<td>2</td>
<td>1</td>
</tr>
<tr>
<td>1</td>
<td>3</td>
<td>12</td>
<td> </td>
</tr>
<tr>
<td>2</td>
<td>13</td>
<td>2</td>
<td> </td>
</tr>
<tr>
<td>3</td>
<td>13</td>
<td> </td>
<td>2</td>
</tr>
<tr>
<td>...</td>
<td> </td>
<td> </td>
<td> </td>
</tr>
<tr>
<td>19</td>
<td> </td>
<td>12</td>
<td>3</td>
</tr>
<tr>
<td>20</td>
<td>1</td>
<td>2</td>
<td>3</td>
</tr>
</tbody>
</table>
<p> </p>
<p>For some starting conﬁgurations, it is not always possible to obtain the goal of strictly increasing order.</p>
<p>对于某些初始情况，是不一定能得到升序排列的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The input will contain some number of test cases.</p>
<p>输入会包含若干测试数据。</p>
<p>A test case consists of two lines. The ﬁrst line contains a positive integer n (n &lt; 8), which is the number of coins.</p>
<p>一个测试数据包含2行，第一行包含一个整数n(n&lt;8)，代表硬币的个数。</p>
<p>We assume that the coins are labeled 1, 2, 3, ...n.</p>
<p>我们可以假设硬币从1-n标号。</p>
<p>The second line contains a list of numbers 1 to n in an arbitrary order, which represents the initial coin conﬁguration.</p>
<p>第二行包含硬币的初始排列顺序。</p>
<p>For the above example, the input test case would be: 3 3 2 1 The end of test cases is indicated by 0 on a line by itself.</p>
<p>对于上面的那个例子，测试数据是</p>
<p>3</p>
<p>3 2 1</p>
<p>0</p>
<p>我们注意到测试数据以0结束来代表没有其他测试数据了。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>For each test case, output one line, which will either contain the minimal number of moves in which Jo can achieve the goal coin line-up, or, if it is not possible to achieve the goal coin line-up, IMPOSSIBLE.</p>
<p>对于输入的每个测试数据，我们需要输出李core能够达到目标序列的最少步数，如果不能达到目标序列的话，输出IMPOSSIBLE。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>3 2 1</p>
<p>2</p>
<p>2 1</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p>
<p>IMPOSSIBLE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>