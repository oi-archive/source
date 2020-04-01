
# Description

<div class="content"><div>可可和卡卡画了一张巨大的N*N的棋盘，他们想在这个棋盘上放尽量多的国际象棋的“車”，使得它们互相不能攻</div>
<div>击到对方（車可以沿着棋盘的横向和纵向攻击）。但这个答案显然就是棋盘的宽度N，于是可可在棋盘上规定了只</div>
<div>有在有限的M个位置上才能放棋子。（其他位置不能放棋子，而車却可以穿过这个位置去攻击其他的棋子）然而这</div>
<div>样也不会难倒两个聪明的小家伙，他们很快算出来这个答案是K。于是卡卡又提出来一个问题：如果我们在这M个可</div>
<div>以放棋子的位置中再去掉一个位置，而仍然保证最多能放下K个車，可行的方案又有多少种呢？ </div>
<div>[任务] 编写一个程序： </div>
<div>从输入文件中读入棋盘的大小和棋盘上可以放棋子的位置信息； </div>
<div>计算出如题卡卡所说的可行方案的数目； </div>
<div>输出你得到的答案。</div></div>

# Input

<div class="content"><div>第一行有两个正整数N和M，分别表示棋盘的大小和可以放棋子的位置数目。 </div>
<div>以下M行，每行用xi和yi两个整数描述一个位置，表示这个位置是棋盘的第xi行第yi列。</div>
<div>同样的一个位置不会被描述两次。</div>
<div>(1&lt;=i&lt;=M, 1&lt;=xi, yi&lt;=N)</div>
<div>1&lt;=N&lt;=200 000, 1&lt;=M&lt;=600 000</div></div>

# Output

<div class="content"><p>输出文件中只有一个整数，表示可行方案的数目。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 2<br/>
1 3<br/>
2 2<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

