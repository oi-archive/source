
# Description

<div class="content"><div>一家餐馆有n张桌子，第i张桌子的座位数为c_i。在一段时间里，先后一共有t群人来到餐馆，任意两群人来的时间</div>
<div>不会一样，你可以认为他们来的时间相差非常大。每群人的人数都在1到g之间等概率随机，这群人会找到一张座位</div>
<div>数最少的，且可以容纳下这群人的，同时没有被其它人占据的桌子。如果找不到这样的桌子，他们就会失望地离开</div>
<div>餐馆。一旦他们坐下了，他们就会一直用餐直到餐馆打烊。比如有3张桌子，容量分别为5,8,9。如果先后来了人数</div>
<div>分别为5,10,3的3群人，最终会有8个人用餐。第一群人占据容量为5的桌子，第二群人失望地离开，第三群人占据</div>
<div>容量为8的桌子。请计算假如t群人每群人的人数都在1到g之间等概率随机，那么最后会留在餐馆用餐的人数的期望</div>
<div>值是多少呢？</div></div>

# Input

<div class="content"><p>第一行包含三个正整数n,g,t(1&lt;=n&lt;=100,1&lt;=g&lt;=200,1&lt;=t&lt;=100)。</p>
<div>第二行包含n个正整数c_1,c_2,...,c_n(1&lt;=c_i&lt;=200)，表示每张桌子的容量。</div>
<div></div></div>

# Output

<div class="content"><p> 输出一行一个实数，即期望人数，绝对或相对误差小于10^{-6}将被接受。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 2<br/>
1 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3.666666667</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

