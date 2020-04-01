
# Description

<div class="content"><p><span style="font-size: medium">有1个方框, 和 N-1 个圆, 排成一个环形.<br/>
初始时, 方框里的数字是 1, 然后延逆时针方向, 依次是 2..N<br/>
一共执行 K 轮游戏, 对于每一轮游戏<br/>
    设当前是第 k 轮游戏.</span></p>
<p><span style="font-size: medium">    然后考虑这一轮开始时, 方框里的数. <br/>
    对这个数 执行 p_k 次交换, 每次都和它当前右边的数交换<br/>
    (但是 方框 和 圆 不交换, 只交换里面的数字)<br/>
    每个数面对的方向是环形的中心<br/>
    p_k 表示 第k小的质数<br/>
最后给定一个 A, 求 游戏全部结束时, A这个数 的 右边的数 和 左边的数</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">    第1行: 3 个整数, N, K, A (1 &lt;= A &lt;= N)</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
    第1行: 两个用 1个空格 隔开的整数, 分别表示 A 右边的数 和 左边的数</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">589 407<br/>
140<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">3 &lt;= N &lt;= 5000000, 1 &lt;= K &lt;= 500000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

