
# Description

<div class="content"><p><span style="font-size: medium">奶牛们在被划分成N行M列(2 &lt;= N &lt;= 100; 2 &lt;= M &lt;= 100)的草地上游走，试图找到整块草地中最美味的牧草。Farmer John在某个时刻看见贝茜在位置 (R1, C1)，恰好T (0 &lt; T &lt;= 15)秒后，FJ又在位置(R2, C2)与贝茜撞了正着。 FJ并不知道在这T秒内贝茜是否曾经到过(R2, C2)，他能确定的只是，现在贝茜在那里。 设S为奶牛在T秒内从(R1, C1)走到(R2, C2)所能选择的路径总数，FJ希望有一个程序来帮他计算这个值。每一秒内，奶牛会水平或垂直地移动1单位距离（奶牛总是在移动，不会在某秒内停在它上一秒所在的点）。草地上的某些地方有树，自然，奶牛不能走到树所在的位置，也不会走出草地。 现在你拿到了一张整块草地的地形图，其中&#39;.&#39;表示平坦的草地，&#39;*&#39;表示挡路的树。你的任务是计算出，一头在T秒内从(R1, C1)移动到(R2, C2)的奶牛可能经过的路径有哪些。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 3个用空格隔开的整数：N，M，T </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1行为M个连续的字符，描述了草地第i行各点的情况，保证 字符是&#39;.&#39;和&#39;*&#39;中的一个 * 第N+2行: 4个用空格隔开的整数：R1，C1，R2，以及C2</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出S，含义如题中所述 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 6<br/>
...*.<br/>
...*.<br/>
.....<br/>
.....<br/>
1 3 1 5<br/>
<br/>
输入说明:<br/>
<br/>
    草地被划分成4行5列，奶牛在6秒内从第1行第3列走到了第1行第5列。<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
    奶牛在6秒内从(1,3)走到(1,5)的方法只有一种（绕过她面前的树）。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver
">Silver<br/>
</a></p></div>

