
# Description

<div class="content"><p>公交车一共经过N（1&lt;=N&lt;=20000）个站点，从站点1一直驶到站点N。K（1&lt;=K&lt;=50000)群奶牛希望搭乘这辆公交车。第i群牛一共有Mi（1&lt;=Mi&lt;=N)只.</p>
<p>他们希望从Si到Ei去。<br/>
公交车只能座C（1&lt;=C&lt;=100）只奶牛。而且不走重复路线，请计算这辆车最多能满足多少奶牛听要求。<br/>
注意：对于每一群奶牛，可以部分满足，也可以全部满足，也可以全部不满足。</p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行： 三个整数： K，N，C。 由空格隔开。 </span></p>
<p><span style="font-size: medium">第2..K+1行：第i+1行，告诉你第i组奶牛的信息： S_i, E_i and M_i。由空格隔开。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一行：可以在庙会乘坐捷运的牛的最大头数 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 15 3<br/>
1 5 2<br/>
13 14 1<br/>
5 8 3<br/>
8 14 2<br/>
14 15 1<br/>
9 12 1<br/>
12 15 2<br/>
4 6 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">捷运可以把2头奶牛从展台1送到展台5，3头奶牛从展台5到展台8， 2头奶牛从展台8 到展台14，1头奶牛从展台9送到展台12，一头奶牛从展台13送到展台14， 一头奶牛从 14送到15。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

