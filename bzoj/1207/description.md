
# Description

<div class="content"><p>鼹鼠是一种很喜欢挖洞的动物，但每过一定的时间，它还是喜欢把头探出到地面上来透透气的。根据这个特点阿Q编写了一个打鼹鼠的游戏：在一个n*n的网格中，在某些时刻鼹鼠会在某一个网格探出头来透透气。你可以控制一个机器人来打鼹鼠，如果i时刻鼹鼠在某个网格中出现，而机器人也处于同一网格的话，那么这个鼹鼠就会被机器人打死。而机器人每一时刻只能够移动一格或停留在原地不动。机器人的移动是指从当前所处的网格移向相邻的网格，即从坐标为（i,j）的网格移向(i-1, j),(i+1, j),(i,j-1),(i,j+1)四个网格，机器人不能走出整个n*n的网格。游戏开始时，你可以自由选定机器人的初始位置。现在你知道在一段时间内，鼹鼠出现的时间和地点，希望你编写一个程序使机器人在这一段时间内打死尽可能多的鼹鼠。</p></div>

# Input

<div class="content"><p>第一行为n（n&lt;=1000）, m（m&lt;=10000），其中m表示在这一段时间内出现的鼹鼠的个数，接下来的m行每行有三个数据time,x,y表示有一只鼹鼠在游戏开始后time个时刻，在第x行第y个网格里出现了一只鼹鼠。Time按递增的顺序给出。注意同一时刻可能出现多只鼹鼠，但同一时刻同一地点只可能出现一只鼹鼠。</p></div>

# Output

<div class="content"><p>仅包含一个正整数，表示被打死鼹鼠的最大数目</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
1 1 1<br/>
2 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

