
# Description

<div class="content"><p><img height="959" alt="" width="695" src="/source/bzoj/2437/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMC8xMS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入的第一行包含两个正整数 n、m。 <br/>
接下来 n行描述初始棋盘。其中第i 行包含 m个字符，每个字符都是大写英文字母&#34;X&#34;、大写英文字母&#34;O&#34;或点号&#34;.&#34;之一，分别表示对应的棋盘格中有黑色棋子、有白色棋子和没有棋子。其中点号&#34;.&#34;恰好出现一次。 <br/>
接下来一行包含一个整数 k（1≤k≤1000） ，表示兔兔和蛋蛋各进行了k次操作。 <br/>
接下来 2k行描述一局游戏的过程。其中第 2i – 1行是兔兔的第 i 次操作（编号为i的操作） ，第2i行是蛋蛋的第i次操作。每个操作使用两个整数x,y来描述，表示将第x行第y列中的棋子移进空格中。 <br/>
输入保证整个棋盘中只有一个格子没有棋子， 游戏过程中兔兔和蛋蛋的每个操作都是合法的，且最后蛋蛋获胜。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出文件的第一行包含一个整数r，表示兔兔犯错误的总次数。 <br/>
接下来r 行按递增的顺序给出兔兔“犯错误”的操作编号。其中第 i 行包含一个整数ai表示兔兔第i 个犯错误的操作是他在游戏中的第 ai次操作。 <br/>
1 ≤n≤ 40， 1 ≤m≤ 40 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：<br/>
1 6 <br/>
XO.OXO <br/>
1 <br/>
1 2 <br/>
1 1 <br/>
样例二：<br/>
3 3 <br/>
XOX <br/>
O.O <br/>
XOX <br/>
4 <br/>
2 3 <br/>
1 3 <br/>
1 2 <br/>
1 1 <br/>
2 1 <br/>
3 1 <br/>
3 2 <br/>
3 3 <br/>
样例三：<br/>
4 4 <br/>
OOXX <br/>
OXXO <br/>
OO.O <br/>
XXXO <br/>
2 <br/>
3 2 <br/>
2 2 <br/>
1 2 <br/>
1 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">样例一：<br/>
1 <br/>
1 <br/>
样例二：<br/>
0<br/>
样例三：<br/>
2<br/>
1<br/>
2<br/>
<br/>
样例1对应图一中的游戏过程<br/>
样例2对应图三中的游戏过程</span></div>

# Hint

<div class="content"><p></p><p><img height="600" alt="" width="537" src="/source/bzoj/2437/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMxMC8yMi5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

