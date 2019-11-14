
# Description

<div class="content"><div>Alice和Bob现在在玩的游戏，主角是依次编号为1到n的n枚硬币。每一枚硬币都有两面，我们分别称之为正面和反</div>
<div>面。一开始的时候，有些硬币是正面向上的，有些是反面朝上的。Alice和Bob将轮流对这些硬币进行翻转操作，且</div>
<div>Alice总是先手。具体来说每次玩家可以选择一枚编号为x，要求这枚硬币此刻是反面朝上的。对于编号x来说，我</div>
<div>们总可以将x写成x=c*2^a*3^b，其中a和b是非负整数，c是与2,3都互质的非负整数，然后有两种选择第一种，选择</div>
<div>整数p,q满足a&gt;=p*q,p&gt;=1且1&lt;=q&lt;=MAXQ,然后同时翻转所有编号为c*2^(a-p*j)*3^b的硬币，其中j=0,1,2,..,q。第</div>
<div>二种，选择整数p,q满足b&gt;=p*q,p&gt;=1且1&lt;=q&lt;=MAXQ,然后同时翻转所有编号为c*2^a*3^(b-p*j)的硬币，其中j=0,1,</div>
<div>2,..,q。可以发现这个游戏不能不先进行下去，当某位玩家无法继续操作上述操作时，便输掉了游戏。作为先手的</div>
<div>Alice，总是希望可以在比赛开始之前就知道自己能否获胜。她知道自己和Bob都是充分聪明的，所以在游戏过程中</div>
<div>两人都会最优化自己的策略并尽量保证自己处于不败的情形中</div></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">本题有多组测试数据，第一行输入一个整数T，表示总的数据组数。之后给出T组数据</div>
<div style="font-size: 11.8181819915771px;">每组数据第一行输入两个整数n,MAXQ</div>
<div style="font-size: 11.8181819915771px;">第二行输入n个整数，第i个数表示第i个硬币的初始状态，0表示反面朝上，1表示正面朝上</div>
<div style="font-size: 11.8181819915771px;">对于100%的数据1&lt;=n&lt;=30000,1&lt;=MAXQ&lt;=20,t&lt;=100。</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">输出共有t行。对于每一组数据来说，如果Alice先手必胜，则输出&#34;win&#34;（不包括引号），否则输出&#34;lose&#34;</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
16 14<br/>
1 0 0 1 0 0 0 0 1 0 0 0 1 0 1 1<br/>
16 14<br/>
0 1 0 0 0 1 1 1 1 1 1 0 1 0 0 1<br/>
16 11<br/>
0 1 0 0 0 1 1 1 0 1 0 0 0 1 0 1<br/>
16 12<br/>
1 1 1 1 1 1 1 1 0 0 1 1 0 1 1 0<br/>
16 4<br/>
1 0 0 1 0 0 1 0 0 0 0 1 0 1 1 0<br/>
16 20<br/>
0 0 0 0 1 0 1 0 0 0 1 0 0 1 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">win<br/>
lose<br/>
win<br/>
lose<br/>
win<br/>
win<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By AHdoc命题 鸣谢Loi_DQS上传xiaoyimi提供题面">By AHdoc命题 鸣谢Loi_DQS上传xiaoyimi提供题面</a></p></div>

