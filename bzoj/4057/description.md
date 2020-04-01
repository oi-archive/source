
# Description

<div class="content"><p>有一些王国陷入了一系列的经济危机。在很多年以前，他们私底下互相借了许多钱。现在，随着他们的负债被揭发，王国的崩溃不可避免地发生了……现在有n个王国，对于每对王国A和B，A欠B的钱被记为d_AB（我们假设有d_BA=-d_AB成立）。如果一个王国入不敷出（即需要支付超过所能获得的钱），它就可能破产。每当一个王国破产，与它相关的所有债务关系都会被去除，无论是正是负。而王国们的破产不是一瞬间完成的，而是第一个王国破产后，接下来可能破产的王国再继续破产，直到剩下的王国经济都是稳定的。不同的结局将取决于谁先破产，尤其是有的结局只会留下一个王国。请你计算，对于每个王国，是否存在一种结局使得该王国是唯一的幸存者。</p></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。</p>
<div>
<div>每组数据第一行一个正整数n，表示有n个王国，1 &lt;= n &lt;= 20。</div>
<div>接下来n行，每行n个整数，第i行第j个整数表示d_ij，保证有d_ii = 0, d_ij = -d_ji, |d_ij| &lt;= 10^6。</div>
</div></div>

# Output

<div class="content"><p>每组数据输出一行，按照升序输出所有可能的王国编号，空格隔开，如果没有一个王国能满足条件，输出一个0。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3<br/>
0 -3 1<br/>
3 0 -2<br/>
-1 2 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

