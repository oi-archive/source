
# Description

<div class="content"><div>白兔喜欢树。</div>
<div>白云喜欢数数。</div>
<div>有 n 只鼠，白兔用 n ? 1根蓝色绳子把它们连成了一棵树，每根蓝色绳子连着两只鼠，白云用 n - 1根红色绳子</div>
<div>把它们连成了一棵树，每根红色绳子连接着两只鼠。白云要给予每只鼠一个数。这个数可以是 [1, y] 中的任意一</div>
<div>个整数。白兔给了白云一个要求：</div>
<div>对于两只鼠 p, q ，若存在一条连接这两只鼠的路径同时属于这两棵树，则 p 和 q必须被给予相同的整数。存在</div>
<div>一条路径同时属于这两棵树指的是：o 存在一个序列 (a1 = p, a2, . . . , am = q) ，使得：对于所有 i ∈ [1</div>
<div>, m ? 1] ，都有 ai和 ai+1 既有一根红色绳子直接相连也有一根蓝色绳子直接相连。</div>
<div>白云想知道，她有多少种给予数的方案呢？</div>
<div>鼠在不停地挣扎，想摆脱绳子的束缚。白云还没有思考出来，鼠便把红色绳子都咬断了。</div>
<div>白兔有些气恼，但是他还是想要知道答案。</div>
<div>他便问白云：对于所有红色绳子的连接方案，答案的总和（即求所有红色绳子连接方案的给予数方案之和）是多少？</div>
<div>鼠在不停地挣扎，想摆脱绳子的束缚。白云还没有思考出来，鼠便把蓝色绳子也咬断了。</div>
<div>白兔有些气恼，但是他还是想要知道答案。他便问白云：对于所有红色和蓝色绳子的连接方案，答案的总和（即求</div>
<div>所有红色和蓝色绳子连接方案的给予数方案之和）是多少？两个方案不同当且仅当存在至少一对鼠，在两种方案中</div>
<div>，这两只鼠之间直接连接的绳子不同（两只鼠之间连接绳子的可能性有 4种：没有绳子直接连接，只有红色绳子直</div>
<div>接连接，只有蓝色绳子直接连接，两种颜色的绳子均直接连接）。</div>
<div>白云哭了。</div>
<div>本题包含三个问题：</div>
<div> 问题 0：已知两棵 n 个节点的树的形态（两棵树的节点标号均为 1 至 n），其中</div>
<div>第一棵树是红树，第二棵树是蓝树。要给予每个节点一个 [1, y] 中的整数，使得</div>
<div>对于任意两个节点 p, q ，如果存在一条路径 (a1 = p, a2, . . . , am = q) 同时属于这</div>
<div>两棵树，则 p, q 必须被给予相同的数。求给予数的方案数。 </div>
<div>问题 1：已知蓝树，对于红树的所有 n^(n?2) 种选择方案，求问题 0 的答案之和</div>
<div>问题 2：对于蓝树的所有 n^(n?2) 种选择方案，求问题 1 的答案之和。</div>
<div>在不同的测试点中，你将可能需要回答不同的问题。我们将用 op 来指代你需要回</div>
<div>答的问题编号（对应上述 0、1、2）。</div>
<div>由于答案可能很大，因此你只需要输出答案对 998244353 取模的结果即可</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个用空格隔开的整数 n, y, op。</div>
<div>如果 op = 0 ，则接下来 2 × (n ? 1) 行，前 (n ? 1) 行每描述一条蓝色绳子，接下来</div>
<div>(n - 1) 行每行描述一条红色绳子。</div>
<div>如果 op = 1 ，则接下来 n ? 1 行，每行描述一条蓝色绳子。</div>
<div>如果 op = 2 ，则接下来没有输入。</div>
<div>描述绳子的各行将包含两个用空格隔开的整数，分别表示被这条绳子连接的两只</div>
<div>鼠的编号。鼠的编号是从 1 开始的。</div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数，表示答案对 998, 244, 353 取模的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">30<br/>
Hint<br/>
3&lt;=n&lt;=1e5<br/>
1&lt;=y&lt;=998244353<br/>
op ∈ {0,1,2}<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Qingyu上传">鸣谢Qingyu上传</a></p></div>

