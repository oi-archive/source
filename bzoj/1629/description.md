
# Description

<div class="content">Farmer John&#39;s N (1 &lt;= N &lt;= 50,000) cows (numbered 1..N) are planning
to run away and join the circus.  Their hoofed feet prevent them
from tightrope walking and swinging from the trapeze (and their
last attempt at firing a cow out of a cannon met with a dismal
failure). Thus, they have decided to practice performing acrobatic
stunts.

The cows aren&#39;t terribly creative and have only come up with one
acrobatic stunt: standing on top of each other to form a vertical
stack of some height.  The cows are trying to figure out the order
in which they should arrange themselves within this stack.

Each of the N cows has an associated weight (1 &lt;= W_i &lt;= 10,000)
and strength (1 &lt;= S_i &lt;= 1,000,000,000).  The risk of a cow
collapsing is equal to the combined weight of all cows on top of
her (not including her own weight, of course) minus her strength
(so that a stronger cow has a lower risk).  Your task is to determine
an ordering of the cows that minimizes the greatest risk of collapse
for any of the cows.


//有三个头牛，下面三行二个数分别代表其体重及力量
//它们玩叠罗汉的游戏，每个牛的危险值等于它上面的牛的体重总和减去它的力量值，因为它要扛起上面所有的牛嘛.
//求所有方案中危险值最大的最小


</div>

# Input

<div class="content">* Line 1: A single line with the integer N.

* Lines 2..N+1: Line i+1 describes cow i with two space-separated
        integers, W_i and S_i.

</div>

# Output

<div class="content">* Line 1: A single integer, giving the largest risk of all the cows in
        any optimal ordering that minimizes the risk.
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
10 3<br/>
2 5<br/>
3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Put the cow with weight 10 on the bottom. She will carry the other<br/>
two cows, so the risk of her collapsing is 2+3-3=2. The other cows<br/>
have lower risk of collapsing.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

