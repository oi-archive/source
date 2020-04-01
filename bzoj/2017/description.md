
# Description

<div class="content"><p><span style="font-size: medium">农夫约翰的奶牛喜欢玩硬币游戏，因此他发明了一种称为“Xoinc”的两人硬币游戏。 初始时，一个有N(5 &lt;= N &lt;= 2,000)枚硬币的堆栈放在地上，从堆顶数起的第I枚硬币的币值为C_i (1 &lt;= C_i &lt;= 100,000)。 开始玩游戏时，第一个玩家可以从堆顶拿走一枚或两枚硬币。如果第一个玩家只拿走堆顶的一枚硬币，那么第二个玩家可以拿走随后的一枚或两枚硬币。如果第一个玩家拿走两枚硬币，则第二个玩家可以拿走1，2，3，或4枚硬币。在每一轮中，当前的玩家至少拿走一枚硬币，至多拿走对手上一次所拿硬币数量的两倍。当没有硬币可拿时，游戏结束。 两个玩家都希望拿到最多钱数的硬币。请问，当游戏结束时，第一个玩家最多能拿多少钱呢？ </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行：1个整数N </span></p>
<p><span style="font-size: medium">第2..N+1行：第i+1行包含1个整数C_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第1行：1个整数表示第1个玩家能拿走的最大钱数。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1<br/>
3<br/>
1<br/>
7<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">样例说明：第1个玩家先取走第1枚，第2个玩家取第2枚；第1个取走第3，4两枚，第2个玩家取走最后1枚。 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

