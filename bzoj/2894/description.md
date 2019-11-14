
# Description

<div class="content"><div><span style="font-size: medium">由于春希对于第二世代操作的不熟练，所以刚使用完invasion process便掉落到了世界线之外，错综复杂的平行世界信息涌入到春希的意识中。春希明白了事件的真相。</span></div>
<div><span style="font-size: medium">在一个冬马与雪菜同时存在的世界里，傲娇的冬马最终还是博得了春希的内心。然而看着好友雪菜的消瘦，内心愧疚的冬马启动了第二世代操作，想找到一个雪菜最终成功的世界，却发现哪里都没有。绝望的冬马决定耗尽自己全部的第二世代操作点数，自创一个没有自己只有雪菜与春希的世界。</span></div>
<div><span style="font-size: medium">虽然这个世界一开始效果很好，春希与雪菜很快的被命运撮合在了一起，然而没有了冬马的雪菜，如没有了大海的沙滩，失去了傍依。</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">虽然世界里没有冬马的存在，但是由于冬马创造时的疏忽，这个世界里的雪菜依然存在着因独占春希而产生的对冬马的愧疚感，这种愧疚感折磨着雪菜，最终雪菜选择了自毁忘记春希。</span></div>
<div><span style="font-size: medium">看着这一切的春希深知不管是三个人一起的快乐，还是两个人独处的甜蜜，都无法消除冬马与雪菜内心的自责，无论如何修改世界，三人都只会更加痛苦，于是春希使用了自己剩余的全部操作点数，念出了key world:WhiteAlbum2，开始了initialization process.</span></div>
<div><span style="font-size: medium">在initialization process中，春希需要整理世界线，才能回归原本的世界。</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">世界线是一棵根节点为1的树，每个节点为1个字符。规定树上的子串为从某个节点（不一定是1号节点）出发往其子节点走所形成的字符串。每一个子串相当于一个平行世界，要想重构世界，就需要知道两个信息：</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; text-indent: -18pt"><span style="font-size: medium">1.<span style="font: 7pt &#39;Times New Roman&#39;">    </span>不同子串的个数</span></div>
<div style="margin: 0cm 0cm 0pt 30pt; text-indent: -18pt"><span style="font-size: medium">2.<span style="font: 7pt &#39;Times New Roman&#39;">    </span>将不同的子串排序后，字典序第k-1小的子串。</span></div>
<div><span style="font-size: medium">如图所示为一个世界线的样例，从4-&gt;5的子串为bb,1-&gt;5的为abb</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 12pt"><span style="font-size: medium">第一行两个整数n，q表示节点个数以及询问个数</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">第二行n个字符，表示编号为i的字符是什么。</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">接下来n-1行表示一棵树。</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">接下来q行，每行一个整数k</span></div></div>

# Output

<div class="content"><div style="text-indent: 12pt"><span style="font-size: medium">第一行为不同支付串个数。</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">接下来q行为q个询问的答案(注意输出的是第k-1小的子串，如果K=1请直接换行)，如果不存在（不包括k=1）输出-1.</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 1<br/>
abcbbaca<br/>
1 2<br/>
2 3<br/>
1 4<br/>
4 5<br/>
4 6<br/>
4 7<br/>
1 8 <br/>
5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
aba<br/>
【数据规模和约定】<br/>
12%：n&lt;=10<br/>
另有48%为一条链;<br/>
100%: n&lt;=250000,q&lt;=50000.	<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

