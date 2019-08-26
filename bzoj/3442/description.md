
# Description

<div class="content"><div><span style="font-size: medium">【背景】</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">坑校准备鼓励学生参加学习小组。</span></div>
<div><span style="font-size: medium">【描述】</span></div>
<div><span style="font-size: medium">    共有n个学生，m个学习小组，每个学生有一定的喜好，只愿意参加其中的一些学习小组，但是校领导为学生考虑，规定一个学生最多参加k个学习小组。财务处的大叔就没那么好了，他想尽量多收钱，因为每个学生参加学习小组都要交一定的手续费，不同的学习小组有不同的手续费。然而，事与愿违，校领导又决定对学习小组组织者进行奖励，若有a个学生参加第i个学习小组，那么给这个学习小组组织者奖励Ci*a^2元。在参与学生（而不是每个学习小组的人数总和）尽量多的情况下，求财务处最少要支出多少钱（若为负数，则输出负数）（支出=总奖励费-总手续费）。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">输入有若干行，第一行有三个用空格隔开的正整数n、m、k。接下来的一行有m个正整数，表示每个Ci。第三行有m个正整数，表示参加每个学习小组需要交的手续费Fi。再接下来有一个n行m列的矩阵，表若第i行j列的数字是1，则表示第i个学生愿意参加第j个学习小组，若为0，则为不愿意。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">输出只有一个整数，为最小的支出。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 3 1<br/>
1 2 3<br/>
3 2 1<br/>
111<br/>
111<br/>
111<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
-2<br/>
【样例解释】<br/>
    参与学生最多为3，每个学生参加一个学习小组，若有两个学生参加第一个学习小组，一个学生参加第二个学习小组（一定要有人参加第二个学习小组），支出为-2，可以证明没有更优的方案了。<br/>
【数据范围与约定】<br/>
100%的数据，0＜n≤100，0＜m≤90，0＜k≤m，0＜Ci≤10，0＜Fi≤100。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By lll6924 at “冬令营后竞速放松赛”">By lll6924 at “冬令营后竞速放松赛”</a></p></div>

