
# Description

<div class="content"><div>公元 8192 年，人类进入星际大航海时代。在不懈的努力之下，人类占领了</div>
<div>宇宙中的 n 个行星，并在这些行星之间修建了 n - 1 条星际航道，使得任意两个</div>
<div>行星之间可以通过唯一的一条路径互相到达。</div>
<div>同时，在宇宙中还有一些空间跳跃点，有些跳跃点已经被发现，还有一些是</div>
<div>未知的，每个跳跃点连接了两个行星，使得这两个行星中的任意一个都可以通过</div>
<div>这个跳跃点到达另外一个行星。这些跳跃点因为充斥着巨大的能量，所以它们很</div>
<div>容易崩溃。</div>
<div>宇宙中还有一些意图毁灭人类的外星人，他们派出了一些使者潜伏在行星</div>
<div>上。现在这些使者想要离开他们各自藏身的行星u，到其他行星 v 去搜集情报。</div>
<div>由于这些使者十分小心， 他们不会经过任意一条属于这两个行星的路径上的星际</div>
<div>航道（即不会走在 u 到 v 路径上的星际航道） 。这样他们就只能借助一些跳跃点</div>
<div>来到达目的地，但是这些外星人的身体十分脆弱，所以他们只能通过最多一个跳</div>
<div>跃点。</div>
<div>现在告诉你若干个按照时间顺序给出的事件，每个事件可能是一个跳跃点又</div>
<div>被发现了，也可能是一个跳跃点崩溃了，还有可能是一个外星使者想离开行星u</div>
<div>到行星v去。</div>
<div>请问每个外星使者有多少条不同的路径可以选择？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数n。</div>
<div>接下来n - 1 行每行两个整数u, v，表示一条星际航道连接行星 u 与行星 v。</div>
<div>接下来一行一个正整数m，表示已经被发现的跳跃点个数。</div>
<div>接下来m行每行两个整数s, t，表示一个跳跃点连接行星 s与行星 t。</div>
<div>接下来一行一个正整数q，表示事件个数。</div>
<div>接下来q 行每行为以下三种事件中的一种：</div>
<div>“1 x y” ：表示有一个连接行星x与行星 y的跳跃点被发现了；</div>
<div>“2 x y” ：表示有一个连接行星 x 与行星 y 的跳跃点崩溃了（保证存在这样</div>
<div>一个跳跃点） ；</div>
<div>“3 x y” ：表示有一个外星使者想从行星x到行星 y去搜集情报。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个外星使者输出一行一个整数， 表示这个外星使者可以选择的不同路径条数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">13<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 5<br/>
5 9<br/>
5 10<br/>
5 11<br/>
10 13<br/>
3 6<br/>
4 7<br/>
4 8<br/>
7 12<br/>
6<br/>
2 4<br/>
10 12<br/>
9 8<br/>
6 7<br/>
3 11<br/>
7 10<br/>
5<br/>
1 1 5<br/>
3 5 4<br/>
2 7 10<br/>
2 10 12<br/>
3 5 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，n ≤ 10^5，m ≤ 5 × 10^4，q ≤ 5 × 10^4 <span style="display: inline! important; float: none; word-spacing: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; orphans: auto; widows: auto; webkit-text-stroke-width: 0px">数据保证x不等于y</span></div><br/>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">数据已加强，By nzhtl1477 ---2016.9.13</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

