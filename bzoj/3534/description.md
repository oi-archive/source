
# Description

<div class="content"><p><span style="font-size: medium">  T国有N个城市，用若干双向道路连接。一对城市之间至多存在一条道路。<br/>
    在一次洪水之后，一些道路受损无法通行。虽然已经有人开始调查道路的损毁情况，但直到现在几乎没有消息传回。<br/>
    辛运的是，此前T国政府调查过每条道路的强度，现在他们希望只利用这些信息估计灾情。具体地，给定每条道路在洪水后仍能通行的概率，请计算仍能通行的道路恰有N-1条，且能联通所有城市的概率。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">  输入的第一行包含整数N。<br/>
  接下来N行，每行N个实数，第i+l行，列的数G[i][j]表示城市i与j之<br/>
间仍有道路联通的概率。<br/>
    输入保证G[i][j]=G[j][i]，且G[i][j]=0；G[i][j]至多包含两位小数。<br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">    输出一个任意位数的实数表示答案。<br/>
    你的答案与标准答案相对误差不超过10^(-4)即视为正确。<br/>
<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
    3<br/>
    0 0.5 0.5<br/>
    0.5 0 0.5<br/>
    0.5 0.5 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    0.375</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">1 &lt; N &lt; =50</span></p><br/>
<p><span style="font-size: medium">数据保证答案非零时，答案不小于10^-4</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 Day 2">Round 1 Day 2</a></p></div>

