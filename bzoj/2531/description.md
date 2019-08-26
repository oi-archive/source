
# Description

<div class="content"><p><font face="Times New Roman" size="3">窘窘因为玩电脑，所以没有做作业。老师很生气，后果很严重。 <br/>
作为惩罚，窘窘收到k1本完全相同的语文作业；k2本完全相同的数学作业；k3本完全相同的英语作业。 <br/>
窘窘认为作业肯定做不完，于是，他就准备将作业分给他的小弟们去做。 <br/>
现在假设窘窘（或他的小弟），总之就是某一个人，收到了a1本完全相同的语文作业；a2本完全相同的数学作业；a3本完全相同的英语作业，他会用如下方法处理： <br/>
当没有语文作业：a1=0时: <br/>
如果只有数学作业a2本，即a3=0，将有f(a2)种方法将作业做完。 <br/>
其中f(0)=1;f(1)=1;其他情况，f(i)=f(i-1)+f(i-1) <br/>
如果只有英语作业a3本，即a2=0，将有g(a3)种方法将作业做完。 <br/>
其中g(0)=1;g(1)=1;其他情况，g(i)=g(i-1)+g(i-2) <br/>
如果同时有数学作业和英语作业，即a2&gt;0,a3&gt;0，则认为这种作业分配方式非法，有0种方法将作业做完。 <br/>
如果没有数学作业或英语作业，即a2=0,a3=0，有1种方法将作业做完。（就是不做啦！） <br/>
当有语文作业：a1&gt;0时： <br/>
只做一本语文作业，将剩下的作业任意分配给他的两个小弟（允许某个小弟一本作业都没有）。注意：这里面，两个小弟是不同的，但任意一门学科的所有作业是相同的。 <br/>
现在假设窘窘收到了k1本完全相同的语文作业；k2本完全相同的数学作业；k3本完全相同的英语作业。他会用如上的方法分配作业。而且保证每个收到作业的人，都有两个小弟（作业一定可以分下去）。对于任意一个小弟，有且仅有一个老大（每个人最多收到作业一次）。现在问：有多少种本质不同的作业划分方案？ <br/>
</font></p></div>

# Input

<div class="content"><p align="left"><font face="Times New Roman" size="3"><br/>
第一行3个正整数分别为k1,k2,k3。 <br/>
</font></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">一个数，即本质不同的作业划分方案数。 <br/>
考虑到大家（还有我自己）不喜欢写高精度，将答案mod 23137 后输出。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 9 8<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
13974<br/>
100%的数据中，k1，k2，k3≤2000。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

