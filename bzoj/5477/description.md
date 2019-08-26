
# Description

<div class="content"><div>
<div>曾经有个星系其中有n个星球，有一颗恒星叫死星，其他行星以它为根构成一颗树。</div>
<div>其中死星的编号是1，其他行星编号为2～n。</div>
<div>每个星球有个发展程度为vi，一开始因为每个星球都至少有文明存在，所以初始的时候vi=1。</div>
<div>定义两个星球之间星际穿越的代价为路径上的发展程度之和，因为发展程度越高需要的过路费越高。</div>
<div>然后会有m次大事件发生，总共有两种类型。</div>
<div>技术爆炸：1 p x表示p号点的发展程度增加x。</div>
<div>技术交流：2 p 表示询问p子树内所有点对的星际穿越的代价之和(mod 10^9+7)。（点对的两点可以相同）</div>
<div>请输出每次技术交流的结果</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n,m。</div>
<div>接下来n-1行，每行两个数u,v表示u,v两颗行星在树上相连。</div>
<div>接下来m行，每行第一个数opt表示事件的类型。</div>
<div>然后根据opt=1,2有2,1个正整数。</div>
<div>pi ≤ n 且 vi &lt; 10^9 + 7 </div>
<div>N,M&lt;=2*10^5</div>
<p></p></div>

# Output

<div class="content"><div>对于每个技术交流的事件输出一行正整数表示答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 <br/>
1 2 <br/>
1 3 <br/>
3 4 <br/>
3 5<br/>
2 5<br/>
2 1<br/>
1 2 3<br/>
2 2<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
33<br/>
4<br/>
10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By zjp_shadow">By zjp_shadow</a></p></div>

