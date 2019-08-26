
# Description

<div class="content"><div></div>
<div>There is an entrance to the ant hill in every chamber with only one corridor leading into (or out of) it. At each entry, there are g groups of m1,m2,...,mg ants respectively. These groups will enter the ant hill one after another, each successive group entering once there are no ants inside. Inside the hill, the ants explore it in the following way:</div>
<div>Upon entering a chamber with d outgoing corridors yet unexplored by the group, the group divides into d groups of equal size. Each newly created group follows one of the d corridors. If d=0, then the group exits the ant hill.</div>
<div>If the ants cannot divide into equal groups, then the stronger ants eat the weaker until a perfect division is possible. Note that such a division is always possible since eventually the number of ants drops down to zero. Nothing can stop the ants from allowing divisibility - in particular, an ant can eat itself, and the last one remaining will do so if the group is smaller than d.</div>
<div>The following figure depicts m ants upon entering a chamber with three outgoing unexplored corridors, dividing themselves into three (equal) groups of floor(m/3) ants each.</div>
<div>A hungry anteater dug into one of the corridors and can now eat all the ants passing through it. However, just like the ants, the anteater is very picky when it comes to numbers. It will devour a passing group if and only if it consists of exactly k ants. We want to know how many ants the anteater will eat.</div>
<div>
<div>给定一棵有n个节点的树。在每个叶子节点，有g群蚂蚁要从外面进来，其中第i群有m[i]只蚂蚁。这些蚂蚁会相继进入树中，而且要保证每一时刻每个节点最多只有一群蚂蚁。这些蚂蚁会按以下方式前进：</div>
<div>·在即将离开某个度数为d+1的点时，该群蚂蚁有d个方向还没有走过，这群蚂蚁就会分裂成d群，每群数量都相等。如果d=0，那么蚂蚁会离开这棵树。</div>
<div>·如果蚂蚁不能等分，那么蚂蚁之间会互相吞噬，直到可以等分为止，即一群蚂蚁有m只，要分成d组，每组将会有floor(m/d)只，如下图。</div>
</div>
<div></div>
<div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;"><img src="source/bzoj/3872/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS9zLnBuZw==.png" width="305" height="228" alt=""/></div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">一只饥饿的食蚁兽埋伏在一条边上，如果有一群蚂蚁通过这条边，并且数量恰为k只，它就会吞掉这群蚂蚁。请计算一共有多少只蚂蚁会被吞掉。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;"></div>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of the standard input contains three integers n, g, k (2&lt;=n,g&lt;=1000000, 1&lt;=k&lt;=10^9), separated by single spaces. These specify the number of chambers, the number of ant groups and the number of ants the anteater devours at once. The chambers are numbered from 1 to n.</div>
<div>The second line contains g integers m[1],m[2],...,m[g](1&lt;=m[i]&lt;=10^9), separated by single spaces, where m[i] gives the number of ants in the i-th group at every entrance to the ant hill. The n-1 lines that follow describe the corridors within the ant hill; the i-th such line contains two integers a[i],b[i] (1&lt;=a[i],b[i]&lt;=n), separated by a single space, that indicate that the chambers no.a[i] and b[i] are linked by a corridor. The anteater has dug into the corridor that appears first on input.</div>
<div>第一行包含三个整数n,g,k,表示点数、蚂蚁群数以及k。</div>
<div>第二行包含g个整数m[1],m[2],...,m[g]，表示每群蚂蚁中蚂蚁的数量。</div>
<div>接下来n-1行每行两个整数，表示一条边，食蚁兽埋伏在输入的第一条边上。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Your program should print to the standard output a single line containing a single integer: the number of ants eaten by the anteater.</div>
<div>一个整数，即食蚁兽能吃掉的蚂蚁的数量。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 5 3<br/>
3 4 1 9 11<br/>
1 2<br/>
1 4<br/>
4 3<br/>
4 5<br/>
4 6<br/>
6 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">21</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

