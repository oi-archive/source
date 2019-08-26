
# Description

<div class="content">The cows have been sent on a mission through space to acquire a new
milking machine for their barn.  They are flying through a cluster
of stars containing N (1 &lt;= N &lt;= 50,000) planets, each with a trading
post.

The cows have determined which of K (1 &lt;= K &lt;= 1,000) types of
objects (numbered 1..K) each planet in the cluster desires, and
which products they have to trade. No planet has developed currency,
so they work under the barter system: all trades consist of each
party trading exactly one object (presumably of different types).

The cows start from Earth with a canister of high quality hay (item
1), and they desire a new milking machine (item K). Help them find
the best way to make a series of trades at the planets in the cluster
to get item K.  If this task is impossible, output -1.

</div>

# Input

<div class="content">* Line 1: Two space-separated integers, N and K.

* Lines 2..N+1: Line i+1 contains two space-separated integers, a_i
        and b_i respectively, that are planet i&#39;s trading trading
        products. The planet will give item b_i in order to receive
        item a_i.

</div>

# Output

<div class="content">* Line 1: One more than the minimum number of trades to get the
        milking machine which is item K (or -1 if the cows cannot
        obtain item K).
</div>

# Sample Input

<div class="content"><span class="sampledata">6 5   //6个星球,希望得到5,开始时你手中有1号货物.<br/>
1 3   //1号星球,希望得到1号货物,将给你3号货物<br/>
3 2<br/>
2 3<br/>
3 1<br/>
2 5<br/>
5 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
The cows possess 4 objects in total: first they trade object 1 for<br/>
object 3, then object 3 for object 2, then object 2 for object 5.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

