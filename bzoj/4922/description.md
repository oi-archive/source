
# Description

<div class="content"><div>卡常数被称为计算机算法竞赛之中最神奇的一类数字，主要特点集中于令人捉摸不透，有时候会让水平很高的选手迷之超时。</div>
<div>普遍认为卡常数是埃及人Qa&#39;a及后人发现的常数。也可认为是卡普雷卡尔(Kaprekar)常数的别称。主要用于求解括号序列问题。</div>
<div>据考证，卡（Qa&#39;a）是古埃及第一王朝的最后一位法老。他发现并研究了一种常数，后世以他的名字叫做卡常数。卡特兰数的起源也是因为卡的后人与特兰克斯结婚，生下来的孩子就叫卡特兰，而他只是发表了祖传的家书而已。Sereja也是卡的后人，提出括号序列问题，也是从家书里得到的资料。然而Sereja为了不让这个秘密公开，于是隐瞒了这道题的真正做法。可是由于卡的后人不是各个都像卡特兰一样爱慕虚荣，这一算法也无法找到。“欲见贤人而不以其道，犹欲其入而闭之门也”。卡之常数的奥秘，需要以一颗诚心去追寻。</div>
<div>现给定n个括号序列，你需要选择若干序列，将它们按一定的顺序从左往右拼接起来，得到一个合法的括号序列。</div>
<div>显然，这个问题可以用卡常数解决，为了检验你是否会卡常数，请写一个程序，计算可以得到的合法的括号序列的长度的最大值。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=300)，表示括号序列的个数。</div>
<div>接下来n行，每行一个长度在[1,300]之间的括号序列，仅由小括号构成。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即最大长度，注意你可以一个序列也不选，此时长度为0。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
())<br/>
((()<br/>
)()</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p><div>按{2,1,3}的顺序拼接得到((()()))()，总长度为10。</div><br/>
<div>新加两组数据by alone_wolf 2017.6.20</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

