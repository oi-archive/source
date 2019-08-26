
# Description

<div class="content"><p> 农夫栋栋近年收入不景气，正在他发愁如何能多赚点钱时，他听到隔壁的小朋友在讨论兔子繁殖的问题。<br/>
<br/>
问题是这样的：第一个月初有一对刚出生的小兔子，经过两个月长大后，这对兔子从第三个月开始，每个月初生一对小兔子。新出生的小兔子生长两个月后又能每个月生出一对小兔子。问第n个月有多少只兔子？<br/>
<br/>
聪明的你可能已经发现，第n个月的兔子数正好是第n个Fibonacci(斐波那契)数。栋栋不懂什么是Fibonacci数，但他也发现了规律：第i+2个月的兔子数等于第i个月的兔子数加上第i+1个月的兔子数。前几个月的兔子数依次为：<br/>
<br/>
1 1 2 3 5 8 13 21 34 …<br/>
<br/>
栋栋发现越到后面兔子数增长的越快，期待养兔子一定能赚大钱，于是栋栋在第一个月初买了一对小兔子开始饲养。<br/>
<br/>
每天，栋栋都要给兔子们喂食，兔子们吃食时非常特别，总是每k对兔子围成一圈，最后剩下的不足k对的围成一圈，由于兔子特别害怕孤独，从第三个月开始，如果吃食时围成某一个圈的只有一对兔子，这对兔子就会很快死掉。<br/>
<br/>
我们假设死去的总是刚出生的兔子，那么每个月的兔子数仍然是可以计算的。例如，当k=7时，前几个月的兔子数依次为：<br/>
<br/>
1 1 2 3 5 7 12 19 31 49 80 …<br/>
<br/>
给定n，你能帮助栋栋计算第n个月他有多少对兔子么？由于答案可能非常大，你只需要告诉栋栋第n个月的兔子对数除p的余数即可。</p></div>

# Input

<div class="content"><p><br/>
<br/>
输入一行，包含三个正整数n, k, p。</p></div>

# Output

<div class="content"><p> <br/>
<br/>
输出一行，包含一个整数，表示栋栋第n个月的兔子对数除p的余数。<br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
<br/>
6 7 100<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
7</span></div>

# Hint

<div class="content"><p></p><p> 1&lt;=N&lt;=10^18</p><br/>
<div>2&lt;=K&lt;=10^6</div><br/>
<div>2&lt;=P&lt;=10^9</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

