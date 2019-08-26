
# Description

<div class="content"><div>有一棵点数为 N 的树，以点 1 为根，且树点有边权。然后有 M 个</div>
<div>操作，分为三种：</div>
<div>操作 1 ：把某个节点 x 的点权增加 a 。</div>
<div>操作 2 ：把某个节点 x 为根的子树中所有点的点权都增加 a 。</div>
<div>操作 3 ：询问某个节点 x 到根的路径中所有点的点权和。</div></div>

# Input

<div class="content"><div>第一行包含两个整数 N, M 。表示点数和操作数。接下来一行 N 个整数，表示树中节点的初始权值。接下来 N-1 </div>
<div>行每行三个正整数 fr, to ， 表示该树中存在一条边 (fr, to) 。再接下来 M 行，每行分别表示一次操作。其中</div>
<div>第一个数表示该操作的种类（ 1-3 ） ，之后接这个操作的参数（ x 或者 x a ） 。</div>
<div></div></div>

# Output

<div class="content"><p>对于每个询问操作，输出该询问的答案。答案之间用换行隔开。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 3 4 5<br/>
1 2<br/>
1 4<br/>
2 3<br/>
2 5<br/>
3 3<br/>
1 2 1<br/>
3 5<br/>
2 1 2<br/>
3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
9<br/>
13<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 对于 100% 的数据， N,M&lt;=100000 ，且所有输入数据的绝对值都不会超过 10^6 。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢bhiaibogf提供">鸣谢bhiaibogf提供</a></p></div>

