
# Description

<div class="content">Farmer John wants to save some blocks of his cows&#39; delicious Wisconsin
cheese varieties in his cellar for the coming winter. He has room
for one tower of cheese in his cellar, and that tower&#39;s height can
be at most T (1 &lt;= T &lt;= 1,000). The cows have provided him with a
virtually unlimited number of blocks of each kind of N (1 &lt;= N &lt;=
100) different types of cheese (conveniently numbered 1..N). He&#39;d
like to store (subject to the constraints of height) the most
valuable set of blocks he possibly can. The cows will sell the rest
to support the orphan calves association.

Each block of the i-th type of cheese has some value V_i (1 &lt;= V_i
&lt;= 1,000,000) and some height H_i (5 &lt;= H_i &lt;= T), which is always
a multiple of 5.

Cheese compresses. A block of cheese that has height greater than
or equal to K (1 &lt;= K &lt;= T) is considered &#34;large&#34; and will crush
any and all of the cheese blocks (even other large ones) located
below it in the tower. A crushed block of cheese doesn&#39;t lose any
value, but its height reduces to just 4/5 of its old height. Because
the height of a block of cheese is always a multiple of 5, the
height of a crushed block of cheese will always be an integer. A
block of cheese is either crushed or not crushed; having multiple
large blocks above it does not crush it more. Only tall blocks of
cheese crush other blocks; aggregate height of a tower does not
affect whether a block is crushed or not.

What is the total value of the best cheese tower FJ can construct?

Consider, for example, a cheese tower whose maximum height can be
53 to be build from three types of cheese blocks. Large blocks are
those that are greater than or equal to 25. Below is a chart of the
values and heights of the various cheese blocks he stacks:

           Type    Value      Height
             1      100         25
             2       20          5
             3       40         10

FJ constructs the following tower:

            Type Height Value
      top -&gt; [1]   25    100
             [2]    4     20   &lt;- crushed by [1] above
             [3]    8     40   &lt;- crushed by [1] above
             [3]    8     40   &lt;- crushed by [1] above
   bottom -&gt; [3]    8     40   &lt;- crushed by [1] above

The topmost cheese block is so large that the blocks below it are
crushed. The total height is:

        25 + 4 + 8 + 8 + 8 = 53

The total height does not exceed 53 and thus is &#39;legal&#39;. The total
value is:

       100 + 20 + 40 + 40 + 40 = 240.

This is the best tower for this particular set of cheese blocks.

John要建一个奶酪塔，高度最大为T。他有N块奶酪。第i块高度为Hi（一定是5的倍数），价值为Vi。一块高度&gt;=K的奶酪被称为大奶酪，一个奶酪如果在它上方有大奶酪（多块只算一次），它的高度就会变成原来的4/5.。。
很显然John想让他的奶酪他价值和最大。。
求这个最大值。。
</div>

# Input

<div class="content">第一行分别是 N T K
接下来N行分别是
Vi Hi
</div>

# Output

<div class="content">一行最大值

</div>

# Sample Input

<div class="content"><span class="sampledata">3 53 25<br/>
100 25<br/>
20 5<br/>
40 10<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">240<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

