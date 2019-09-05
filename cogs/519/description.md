# 题目描述


<p>
<span style="font-size: 14pt; font-family: " courier="" new";="" mso-font-kerning:="" 0pt"="" lang="EN-US">2．乌龟棋</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">(tortoise.pas/c/cpp)</span> 
</p>
<p>
【问题描述】
</p>
<p>
小明过生日的时候，爸爸送给他一副乌龟棋当作礼物。
</p>
<p>
乌龟棋的棋盘是一行N个格子，每个格子上一个分数（非负整数）。棋盘第1格是唯一的起点，第N格是终点，游戏要求玩家控制一个乌龟棋子从起点出发走到终点。
</p>
<p>
……
</p>
<p>
1 2 3 4 5……N
</p>
<p>
乌龟棋中M张爬行卡片，分成4种不同的类型（M张卡片中不一定包含所有4种类型的卡片，见样例），每种类型的卡片上分别标有1、2、3、4四个数字之一，表示使用这种卡片后，乌龟棋子将向前爬行相应的格子数。游戏中，玩家每次需要从所有的爬行卡片中选择一张之前没有使用过的爬行卡片，控制乌龟棋子前进相应的格子数，每张卡片只能使用一次。
</p>
<p>
游戏中，乌龟棋子自动获得起点格子的分数，并且在后续的爬行中每到达一个格子，就得到该格子相应的分数。玩家最终游戏得分就是乌龟棋子从起点到终点过程中到过的所有格子的分数总和。
</p>
<p>
很明显，用不同的爬行卡片使用顺序会使得最终游戏的得分不同，小明想要找到一种卡片使用顺序使得最终游戏得分最多。
</p>
<p>
现在，告诉你棋盘上每个格子的分数和所有的爬行卡片，你能告诉小明，他最多能得到多少分吗？
</p>
<p>
【输入】
</p>
<p>
输入文件名tortoise.in。输入文件的每行中两个数之间用一个空格隔开。
</p>
<p>
第1行2个正整数N和M，分别表示棋盘格子数和爬行卡片数。
</p>
<p>
第2行N个非负整数，a1, a2,……, aN，其中ai表示棋盘第i个格子上的分数。
</p>
<p>
第3行M个整数，b1,b2,……, bM，表示M张爬行卡片上的数字。
</p>
<p>
输入数据保证到达终点时刚好用光M张爬行卡片，即N−1=ΣMib1。
</p>
<p>
【输出】
</p>
<p>
输出文件名tortoise.out。
</p>
<p>
输出只有1行，1个整数，表示小明最多能得到的分数。
</p>
<p>
【输入输出样例1】
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">tortoise.in</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">9 5</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">6 10 14 2 8 8 18 5 17</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">1 3 1 2 1</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US"> tortoise.out<br/>
</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">73</span> 
</p>
<p>
【输入输出样例1说明】
</p>
<p>
小明使用爬行卡片顺序为1，1，3，1，2，得到的分数为6+10+14+8+18+17=73。注意，
</p>
<p>
由于起点是1，所以自动获得第1格的分数6。
</p>
<p>
【输入输出样例2】
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">tortoise.in</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">13 8</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">4 96 10 64 55 13 94 53 5 24 89 8 30</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">1 1 1 1 1 2 4 1</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">tortoise.out</span> 
</p>
<p>
<span style="font-family: " courier="" new";="" mso-bidi-font-size:="" 10.5pt;="" mso-font-kerning:="" 0pt"="" lang="EN-US">455</span> 
</p>
<p>
【数据范围】
</p>
<p>
对于30%的数据有1≤N≤30，1≤M≤12。
</p>
<p>
对于50%的数据有1≤N≤120，1≤M≤50，且4种爬行卡片，每种卡片的张数不会超过20。
</p>
<p>
对于100%的数据有1≤N≤350，1≤M≤120，且4种爬行卡片，每种卡片的张数不会超过40；0≤ai≤100，1≤i≤N；1≤bi≤4，1≤i≤M。输入数据保证N−1=ΣMib。
</p>
<p>
<br/>
</p>
