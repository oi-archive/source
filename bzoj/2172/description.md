
# Description

<div class="content"><p>《超级马里奥兄弟》是任天堂于1985年出品的著名横版过关游戏，作为1983年游戏《马里奥兄弟》的续作在FC红白机上推出。在游戏《超级马里奥兄弟》中，玩家控制马里奥从库巴手上设法营救Peach公主。今年是《超级马里奥兄弟》发行25周年了，任天堂推出了25周年纪念合集。lqp也想来凑热闹，他开发了一个小游戏，叫做“Mario填格子”。游戏是这样的，Boss Wario给出了一个3*3的小格子，在左上角填上了M，右下角填上了N。现在开始倒计时了，你必须给剩余的几个格子填上一些正整数，对于每个格子（格子里的数是X）满足：如果它左边相邻有一个数Y，那么Y|X（表示Y整除X）。如果它上面相邻有一个数Z，那么Z|X。不存在和它填有相同数字的格子。比如下面就是一个M=1, N=36的满足条件的填法： 1 2 4 3 6 12 9 18 36</p></div>

# Input

<div class="content"><p>输入包含若干行，以EOF结束。每行包含两个正整数M和N，分别是左上角的数字和右下角的数字。</p></div>

# Output

<div class="content"><p>如果Mario能够获胜，输出“Mario_wins!”，输出“ Wario_wins!”。每个数据输出一个空行。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 36<br/>
4 36 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Mario_wins!<br/>
<br/>
Wario_wins!</span></div>

# Hint

<div class="content"><p></p><p>10%数据满足：1≤M, N≤9 30%数据满足：1≤M, N≤100 50%数据满足：1≤M, N≤100000 100%数据满足：最多10组测试数据，1≤M, N≤1017 其中有10%数据N=M*pT（p的t次方）。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

