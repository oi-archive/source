
# Description

<div class="content"><p class="NOI"></p>
<p class="NOI">假设一开始，荷官拿出了一副新牌，这副牌有N张不同的牌，编号依次为1到N。由于是新牌，所以牌是按照顺序排好的，从牌库顶开始，依次为1, 2,……直到N，N号牌在牌库底。为了发完所有的牌，荷官会进行N次发牌操作，在第i次发牌之前，他会连续进行R_i次销牌操作，R_i由输入给定。请问最后玩家拿到这副牌的顺序是什么样的？</p>
<p class="NOI">举个例子，假设N = 4，则一开始的时候，牌库中牌的构成顺序为{1, 2, 3, 4}。</p>
<p class="NOI">假设R1=2，则荷官应该连销两次牌，将1和2放入牌库底，再将3发给玩家。目前牌库中的牌顺序为{4, 1, 2}。</p>
<p class="NOI">假设R2=0，荷官不需要销牌，直接将4发给玩家，目前牌库中的牌顺序为{1,2}。</p>
<p class="NOI">假设R3=3，则荷官依次销去了1, 2, 1，再将2发给了玩家。目前牌库仅剩下一张牌1。</p>
<p class="NOI">假设R4=2，荷官在重复销去两次1之后，还是将1发给了玩家，这是因为1是牌库中唯一的一张牌。</p>
<p class="NOI2"></p>
<p></p></div>

# Input

<div class="content"><p class="NOI">第1行，一个整数N，表示牌的数量。第2行到第N + 1行，在第i + 1行，有一个整数R_i， 0≤R_i&lt;N</p>
<p></p></div>

# Output

<div class="content"><p class="NOI">第1行到第N行：第i行只有一个整数，表示玩家收到的第i张牌的编号。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2<br/>
0<br/>
3<br/>
2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
2<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=70万</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

