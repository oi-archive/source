
# Description

<div class="content"><div>《隐形的整数》是一个简单的猜数游戏。在这个游戏中，给定n个提示，玩家将尝试去猜一个仅包含自然数1到9的</div>
<div>数字序列，满足所有n个提示。每个提示是一个包含若干互不相同的1到9之间的整数序列，它是这样生成的：</div>
<div></div>
<div>1.随机选择一个序列中的位置作为起点。</div>
<div></div>
<div>2.随机选择任意一个方向，左或者右。</div>
<div></div>
<div>3.从起点开始沿着选定的方向走，遍历完这个方向的每个数字，将每个数字第一次出现的顺序记录下来。</div>
<div></div>
<div>请找到长度最短的满足所有n个提示的序列。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=10)，表示提示的个数。</div>
<div>接下来n行，每行若干个互不相同的1到9之间的整数，依次表示每个提示，每一行以0为终止。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即最短长度，若无解则输出-1。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 0<br/>
3 4 0<br/>
1 4 3 0<br/>
3 1 4 2 0<br/>
1 2 4 3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
一个可行的序列是(1,2,1,4,1,3,4)。<br/>
对于提示序列(1,2)，可以选择位置3，然后往左走。<br/>
对于提示序列(3,4)，可以选择位置6，然后往右走。<br/>
对于提示序列(1,4,3)，可以选择位置3，然后往右走。<br/>
对于提示序列(3,1,4,2)，可以选择位置6，然后往左走。<br/>
对于提示序列(1,2,4,3)，可以选择位置1，然后往右走。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

