
# Description

<div class="content"><p>你办了一场比赛，有n给人参加，只有一道题，有m个数据点，标号为1~m，每个测试点都有一个分数a[i]。现在所</p>
<div>有选手已经提交了程序并且测评完了，你知道每个人都能通过哪些测试点。你现在要安排捆绑测试的方式，把数据</div>
<div>点划分为若干个连续的区间，每个区间至少有一个测试点。每个区间只要有一个测试点错误就不会得分，如果所有</div>
<div>点都正确得分为所有测试点的分数的和。你的目的是最小化所有人的得分和。你需要对1&lt;=i&lt;=S，输出当把所有测</div>
<div>试点划分为i组时，最小的所有人分数和。</div></div>

# Input

<div class="content"><div>第一行三个整数n,m,S</div>
<div>接下来一行m个整数，代表a[i]</div>
<div>接下来n行每行一个长度为m的01串，代表第i个人是否通过了第j个测试点</div>
<div></div>
<div>n&lt;=50</div>
<div>m&lt;=200000</div>
<div>S&lt;=min(50,m)</div>
<div>a[i]&lt;=10000,sigma a[i]*n&lt;=2000000000</div></div>

# Output

<div class="content"><div>S行，每行一个整数，代表当划分为i个捆绑测试点时所有人分数和的最小值</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 3<br/>
4 3 5<br/>
101<br/>
110</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
8<br/>
16</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢alone_wolf提供翻译">鸣谢alone_wolf提供翻译</a></p></div>

