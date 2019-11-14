
# Description

<div class="content">
有一个100 * 100的棋盘，其中左下角的编号为(0, 0), 右上角编号为(99, 99)。棋盘上有N个Queen，最开始第i个Queen的位置为(Xi, Yi)。现在有两个玩家依次来操作，每一次一个玩家可以选择其中一个Queen，将它跳到(Xi – k, Yi)或(Xi, Yi - k)或(Xi – k, Yi - k), 其中k &gt; 0。注意在游戏的过程中，一个格子里面可能出现多个Queen。如果谁先将任意一个Queen移动到(0, 0), 谁就获胜。问先手必胜还是后手必胜?
</div>

# Input

<div class="content">注意本题是多组数据。
第一行有一个数T, 表示数据组数。
接下来有T组数据，每组数据的第一行一个正整数N表示Queen的个数。接下来N行每行两个数表示第i个Queen的初始位置Xi, Yi(0 &lt;= Xi &lt;= 99, 0 &lt;= Yi &lt;= 99)。
</div>

# Output

<div class="content">对于每一组数据，你需要输出是先手必胜还是后手必胜。
如果是先手必胜，输出“^o^“, 如果是后手必胜，输出”T_T”。
</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2<br/>
3 4<br/>
3 5<br/>
3<br/>
3 2<br/>
4 2<br/>
3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">^o^<br/>
T_T<br/>
数据范围<br/>
T &lt;= 10, N &lt;= 1000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

