
# Description

<div class="content"><p>有n个人在轮流玩赌博机，一开始编号为i的人有a[i]元钱。赌博机可以抽象为一个长度为m的仅包含1和-1的序列，若抽到1，那么你将得到1块钱；若抽到-1，你将输掉1块钱。<br/>
第1局，第1个人会抽到序列中的第1项；第2局，第2个人会抽到序列中的第2项；第3局，第3个人会抽到序列中的第3项......即：第i个人抽完后轮到第i+1个人去抽，特别地，第n个人抽完后轮到第1个人去抽。序列第i项被抽到之后，下一个被抽到的将会是第i+1项，特别地，序列第m项被抽到之后，下一个被抽到的将会是第1项。<br/>
如果在某一轮，有个人输光了所有的钱，那么这场赌博游戏就会结束，请求出游戏在哪一轮结束，或者判断这个游戏会永远进行下去。</p></div>

# Input

<div class="content"><p>第一行包含一个正整数n(1&lt;=n&lt;=1000000)，表示玩家的个数。<br/>
第二行包含n个正整数a[1],a[2],...,a[n](1&lt;=a[i]&lt;=1000000)，依次表示每个玩家一开始持有的钱数。<br/>
第一行包含一个正整数m(1&lt;=m&lt;=1000000)，表示序列的长度。<br/>
第四行包含一个长度为m的仅包含W和P的字符串，表示这个序列，其中W表示1，P表示-1。</p></div>

# Output

<div class="content"><p>若游戏会永远进行下去，输出-1。否则输出游戏在哪一轮结束。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 3 2 1<br/>
3<br/>
WPP</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

