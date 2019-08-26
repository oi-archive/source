
# Description

<div class="content"><p><span style="font-size: medium">Arietta 的命运与她的妹妹不同,在她的妹妹已经走进学院的时候,她仍然留在山村中。<br/>
但是她从未停止过和恋人 Velding 的书信往来。一天,她准备去探访他。<br/>
对着窗外的阳光,临行前她再次弹起了琴。<br/>
她的琴的发声十分特殊。<br/>
让我们给一个形式化的定义吧。<br/>
所有的 n 个音符形成一棵由音符 C ( 1 号节点) 构成的有根树,每一个音符有一个音高 Hi 。<br/>
Arietta 有 m 个力度,第 i 个力度能弹出 Di 节点的子树中,音高在 [Li,Ri] 中的任意一个音符。<br/>
为了乐曲的和谐,Arietta 最多会弹奏第 i 个力度 Ti 次。<br/>
Arietta 想知道她最多能弹出多少个音符。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">输入共 m + 3 行。<br/>
第一行两个整数 n, m ,意义如题目所述。<br/>
第二行 n - 1 个整数 Pi ,表示节点 i ( i = 2 . . . n ) 的父亲节点的编号。<br/>
第三行 n 个整数 Hi 。<br/>
接下来的 m 行,每行四个整数 Li,Ri,D,Ti<br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">输出一个整数表示 Arietta 最多能弹奏多少音符。<br/>
数据范围与约定<br/>
对于 100% 的数据,1 ≤ n, m ≤ 10000 。<br/>
对于所有数据,1 ≤ Hi , Ti , Pi ≤ n, 1 ≤ Li ≤ Ri ≤ n 。</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
1 1 2 2<br/>
5 3 2 4 1<br/>
1 3 2 1<br/>
3 5 1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">第一个力度弹奏音符5，第二个力度弹奏音符1,2,4。 </span></p><br/>
<p><span style="font-size: medium">数据范围与约定<br/><br/>
对于 100% 的数据,1 ≤ n, m ≤ 10000 。<br/><br/>
对于所有数据1&lt;=Hi,Ti,Pi&lt;=N,1&lt;=Li&lt;=Ri&lt;=N<br/><br/>
 <br/><br/>
 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Shinrein祭 #1">Shinrein祭 #1</a></p></div>

