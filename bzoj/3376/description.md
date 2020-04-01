
# Description

<div class="content"><div><span style="font-size: medium">    约翰和贝茜在玩一个方块游戏．编号为1到n的n(1≤n≤30000)个方块正放在地上．每个构成一个立方柱．</span></div>
<div><span style="font-size: medium">   游戏开始后，约翰会给贝茜发出P(1≤P≤100000)个指令．指令有两种：</span></div>
<div><span style="font-size: medium">    1．移动(M)：将包含X的立方柱移动到包含Y的立方柱上．</span></div>
<div><span style="font-size: medium">    2．统计(C):统计名含X的立方柱中，在X下方的方块数目．</span></div>
<div><span style="font-size: medium">    写个程序帮贝茜完成游戏．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入P，之后P行每行输入一条指令．形式为“M X Y”或者“C X”</span></div>
<div><span style="font-size: medium">    输入保证不会有将立方柱放在自己头上的指令．</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    每一行，对于每个统计指令，输出其结果．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
M 1 6<br/>
C 1<br/>
M 2 4<br/>
M 2 6<br/>
C 3<br/>
C 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Green">Green</a></p></div>

