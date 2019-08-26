
# Description

<div class="content"><p>作为一个富有经营头脑的富翁，小L决定从本国最优秀的经理中雇佣一些来经营自己的公司。这些经理相互之间合作有一个贡献指数,（我们用Ei,j表示i经理对j经理的了解程度），即当经理i和经理j同时被雇佣时，经理i会对经理j做出贡献，使得所赚得的利润增加Ei,j。当然，雇佣每一个经理都需要花费一定的金钱Ai，对于一些经理可能他做出的贡献不值得他的花费，那么作为一个聪明的人，小L当然不会雇佣他。 然而，那些没有被雇佣的人会被竞争对手所雇佣，这个时候那些人会对你雇佣的经理的工作造成影响，使得所赚得的利润减少Ei,j（注意：这里的Ei,j与上面的Ei,j 是同一个）。 作为一个效率优先的人，小L想雇佣一些人使得净利润最大。你可以帮助小L解决这个问题吗？</p></div>

# Input

<div class="content"><p>第一行有一个整数N&lt;=1000表示经理的个数 第二行有N个整数Ai表示雇佣每个经理需要花费的金钱 接下来的N行中一行包含N个数，表示Ei,j，即经理i对经理j的了解程度。（输入满足Ei,j=Ej,i）</p></div>

# Output

<div class="content"><p>第一行包含一个整数，即所求出的最大值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">    3<br/>
    3 5 100<br/>
    0 6 1<br/>
    6 0 2<br/>
    1 2 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    1<br/>
【数据规模和约定】<br/>
20%的数据中N&lt;=10<br/>
50%的数据中N&lt;=100<br/>
100%的数据中 N&lt;=1000， Ei,j&lt;=maxlongint,  Ai&lt;=maxlongint<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=版权所有者： 林衍凯
">版权所有者： 林衍凯<br/>
</a></p></div>

