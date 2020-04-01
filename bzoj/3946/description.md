
# Description

<div class="content"><div>
<div>小K因为学习OI认识了两位神犇，他们分别叫做小H和小Y。两位神犇平时是这么对待小K的：</div>
<div>“这不是道傻逼题么”</div>
<div>“这都不会做你智商堪忧啊”</div>
<div>“。。。。。。”</div>
<div>小K因此对生活失去了信心。最近两位神犇没什么题刷，于是他们开始用自己做题剩下的史诗级智商来享受生活的快乐——研究游戏开发了。</div>
<div>由于两位神犇太神，不久他们就创造了新的游戏。游戏一开始会给由你N个非空串构成的序列，然后你要进行M次操作。操作分为两种：</div>
<div>第一种操作Insert(L,R,S)：表示在[L,R]之间的所有串前都加上一个新的非空串S。</div>
<div>第二种操作Query(L,R)：询问[L,R]之间所有串的最长公共前缀。如果L=R，则输出对应串的长度。</div>
<div>两位神犇分分钟就把这个游戏玩通了。于是他们准备虐一虐小K，让他也来玩玩。不出所料，小K被虐得头昏眼花，于是他找到你，看你能不</div>
<div>能帮他一把。小K还需要为NOIP一等奖而奋斗呢。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第1行包含两个正整数N，M。接下来的N行每行都包含一个非空的串S，表示第i个初始的串。再接下来的M行每行的</div>
<div>开头都有一个字母type，type=`I&#39;表示这行对应一个Insert操作，而type=`Q&#39;时对应一个Query操作。接下来会从</div>
<div>左到右依次给出这个操作的参数。</div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每一个Query操作，输出一行。一行包含一个正整数，表示这组询问的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
noi<br/>
noip<br/>
Q 1 2<br/>
I 2 2 ctsc<br/>
Q 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
0</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>令st表示初始时所有串的长度之和，$sum$表示所有$Insert$操作中所给串的长度之和。</div><br/>
<div>对于25%的数据，满足N,M&lt;=1000, st,sum&lt;=3000。</div><br/>
<div>对于50%的数据，满足N,M&lt;=20000, st,sum&lt;=40000。</div><br/>
<div>对于100%的数据，满足N,M&lt;=50000,<span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">st+sum&lt;=600000</span></div><br/>
<div>保证所有的串都只包含小写英文字母。</div><br/>
<div>保证有一些数据是随机的。</div><br/>
</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测">2014年国家集训队十五人互测</a></p></div>

