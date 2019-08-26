
# Description

<div class="content"><div>不远的一年前，小V还是一名清华集训的选手，坐在机房里为他已如风中残烛的OI生涯做最后的挣扎。而如今，他</div>
<div>已成为了一名光荣的出题人。他感到非常激动，不禁感叹道：“Helloworld!”。</div>
<div></div>
<div>小V有n道题，他的题都非常毒瘤，所以关爱选手的ufozgg打算削弱这些题。为了逃避削弱，小V把他的毒瘤题都藏</div>
<div>到了一棵n个节点的树里（节点编号从1至n），这棵树上的所有节点与小V的所有题一一对应。小V的每一道题都有</div>
<div>一个毒瘤值，节点i（表示标号为i的树上节点，下同）对应的题的毒瘤值为ai。魔法师小V为了保护他的题目，</div>
<div>对这棵树施了魔法，这样一来，任何人想要一探这棵树的究竟，都必须在上面做跳跃操作。每一次跳跃操作包含一</div>
<div>个起点s、一个终点t和一个步频k，这表示跳跃者会从s出发，在树上沿着简单路径多次跳跃到达t，每次跳跃，如</div>
<div>果从当前点到t的最短路长度不超过k，那么跳跃者就会直接跳到t，否则跳跃者就会沿着最短路跳过恰好k条边。既</div>
<div>然小V把题藏在了树里，ufozgg就不能直接削弱题目了。他就必须在树上跳跃，边跳跃边削弱题目。ufozgg每次跳</div>
<div>跃经过一个节点（包括起点s，当s=t的时候也是如此），就会把该节点上的题目的毒瘤值开根并向下取整：即如果</div>
<div>他经过了节点i，他就会使ai=trunc(sqrt(ai))。这种操作我们称为削弱操作。ufozgg还会不时地希望知道他对题</div>
<div>目的削弱程度。因此，他在一些跳跃操作中会放弃对题目的削弱，转而统计该次跳跃经过节点的题目毒瘤值总和。</div>
<div>这种操作我们称为统计操作。吃瓜群众绿绿对小V的毒瘤题和ufozgg的削弱计划常感兴趣。他现在想知道ufozgg每</div>
<div>次做统计操作时得到的结果。你能帮帮他吗？</div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行一个正整数n，表示树的节点数。</div>
<div>接下来一行n个用空格隔开的正整数a1,a2,…,an，依次描述每个节点上题目的毒瘤值。</div>
<div>接下来n-1行，描述这棵树。每行2个正整数u,v描述一条树上的边(u,v)</div>
<div>（保证1≤u,v≤n，保证这n-1条边构成了一棵树）</div>
<div>接下来一行一个正整数Q，表示ufozgg的操作总数。</div>
<div>接下来Q行按ufozgg执行操作的先后顺序依次描述每个操作，</div>
<div>每行4个用空格隔开的整数op,s,t,k，表示ufozgg此次跳跃的起点为s，终点为t，步频为k。</div>
<div>如果op=0，表示这是一次削弱操作；</div>
<div>如果op=1表示这是一次统计操作。</div>
<div>n≤50000,Q≤400000，1≤ai≤10^13，对于所有的操作保证0≤op≤1，1≤s,t,k≤n</div>
<p></p></div>

# Output

<div class="content"><div>对于每个统计操作，输出一行一个整数，表示此次统计操作统计到的所有题的毒瘤值总和。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 5<br/>
1 2<br/>
2 3<br/>
3 4<br/>
2 5<br/>
5<br/>
1 1 4 1<br/>
1 1 4 2<br/>
0 1 5 2<br/>
1 2 4 5<br/>
1 1 5 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
8<br/>
6<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

