
# Description

<div class="content"><div><span style="font-size: medium">【背景】</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">有n个无聊人士围成一圈，有一个球将被他们传来传去。</span></div>
<div><span style="font-size: medium">【描述】</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">当被传到球之后，不同的人会做出不同的动作。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第1类人，顺着传来的方向传给下一个人。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第2类人，逆着传来的方向传给上一个人。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第3类人，顺着传来的方向传给下面第二个人。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第4类人，逆着传来的方向传给上面第二个人。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">现不知是从哪个人开始传，及开始传的方向，求有哪些人无论如何，最多只能碰到一次球（开始传球的人算碰到了一次球）。（第3、4类人发球也是越过和自己相邻的人传给第二个人）。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">输入有2行，第一行有一个正整数n。第二行有n个用空格隔开的正整数，第i个数字表示顺指针的第i个人是第几类人。</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">输出有2行，第一行有一个正整数m，表示最多只能碰到一次球的人的个数。第二行有m个正整数，表示哪些人最多只能碰到一次球，从小到大输出。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
【数据范围与约定】<br/>
100%的数据，4＜n≤500000。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By lll6924 at “冬令营后竞速放松赛”">By lll6924 at “冬令营后竞速放松赛”</a></p></div>

