
# Description

<div class="content">Emmy在一个养猪场工作。这个养猪场有M个锁着的猪圈，但Emmy并没有钥匙。顾客会到养猪场来买猪，一个接着一个。每一位顾客都会有一些猪圈的钥匙，他们会将这些猪圈打开并买走固定数目的猪。
所有顾客有的钥匙和他们需要买猪的数量在事先都告诉了Emmy，于是Emmy要订一个计划，使得卖出去的猪最多。
买卖的过程是这样的：一个顾客前来，并打开所有他可以打开的猪圈。然后Emmy从这些猪圈里牵出固定数目的猪卖给顾客（最多只能和顾客需要数相等），并可以重新安排这些开着的猪圈中的猪。
每个猪圈可以存放任意数目的猪。
写一个程序，使得Emmy能够卖出去尽可能多的猪。
</div>

# Input

<div class="content">第一行有两个整数：M和N，表示猪圈数和顾客数。
第二行有M个整数，表示每个猪圈初始时有多少猪。
接下来的N行按照前来的次序描述了每一个顾客，每行的格式如下：
A K1 K2…KA B
A表示该顾客拥有的钥匙数，K1...KA表示每个钥匙所对应的猪圈，B表示该顾客需要购买的猪的数目。
</div>

# Output

<div class="content">仅包含一个整数，即最多能卖出去的猪的数目。

</div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
3 1 10<br/>
2 1 2 2<br/>
2 1 3 3<br/>
1 2 6	<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p>1 ≤ M ≤ 1000<br/>
1 ≤ N ≤ 100<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

