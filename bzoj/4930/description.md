
# Description

<div class="content"><div>给定一个n×n的棋盘，棋盘上每个位置要么为空要么为障碍。定义棋盘上两个位置(x,y),(u,v)能互相攻击当前仅</div>
<div>当满足以下两个条件：</div>
<div>1:x=u或y=v</div>
<div>2:对于(x,y)与(u,v)之间的所有位置，均不是障碍。</div>
<div>现在有q个询问，每个询问给定ki，要求从棋盘中选出ki个空位置来放棋子，问最少互相能攻击到的棋子对数是多少？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数n。</div>
<div>接下来输入一个n×n的字符矩阵，一个位置若为.，则表示这是一个空位置，若为#，则为障碍。</div>
<div>第n+2行输入一个整数q代表询问个数。</div>
<div>接下来q行，每行一个整数k，代表要放的棋子个数。</div>
<div>n ≤ 50, q ≤ 10000, k ≤ 棋盘中空位置数量</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出共q行，每行代表对应询问的最少的互相能攻击到的棋子对数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
..#.<br/>
####<br/>
..#.<br/>
..#.<br/>
1 7</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

