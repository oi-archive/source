
# Description

<div class="content"><div>今年秋天，约翰带着奶牛们去玩玉米迷宫。迷宫可分成NxM个格子，有些格子种了玉 米，种宥玉米的格子无法通行</div>
<div>。迷宫的四条边界上都是种了玉米的格子，其屮只有一个格子 没种，那就是出口。在这个迷宫里，有一些神奇的</div>
<div>传送点6每个传送点由一对点组成，一旦 走入传送点的某个结点，机器就会强制把你送到传送点的另一头去。所有</div>
<div>的传送点都是双向 的，如果你定到了另一头，机器也会把你送回来。奶牛在一个单位的时间内只能向相邻的四个</div>
<div>方向移动一格，不过传送机传送是瞬间完成 的。现在W西在迷宫里迷路了，她只知道目前的位罝在哪里，请你帮助</div>
<div>她用最短的时间走出 迷宫吧。</div></div>

# Input

<div class="content"><div>第一行：两个用空格分开的整数：N和M,2 </div>
<div>第二行到N+1行：第i+1行有M个连续的字符，描述了迷宫第i行的信息。</div>
<div>其中&#34;#&#34;代 表不能通行的玉米地， &#34;.&#34;代表可以通行的草地，</div>
<div>&#34;@&#34;代表贝西的起始位罝，&#34;=&#34;代表迷宫出口， </div>
<div>大写字母“A”到“Z”总是成对出现的，代表一对传送点 </div></div>

# Output

<div class="content"><p align="left"><font size="3" face="Times New Roman">一个整数，表示贝西走出迷宫的最短时间，保证逃离迷宮的路线一定存在</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
###=##<br/>
#.W.##<br/>
#.####<br/>
#.@W##<br/>
######<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
//从起点向右走，通过w传送，再从另一端 走出迷宫</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

