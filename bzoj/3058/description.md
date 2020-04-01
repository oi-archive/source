
# Description

<div class="content"><p><span style="font-size: medium">魔杖护法Freda融合了四件武器，于是魔杖顶端缓缓地生出了一棵四叶草，四片叶子幻发着淡淡的七色光。圣剑护法rainbow取出了一个圆盘，圆盘上镶嵌着N颗宝石，编号为0~N-1。第i颗宝石的能量是Ai。如果Ai&gt;0，表示这颗宝石能量过高，需要把Ai的能量传给其它宝石；如果Ai&lt;0，表示这颗宝石的能量过低，需要从其它宝石处获取-Ai的能量。保证∑Ai =0。只有当所有宝石的能量均相同时，把四叶草魔杖插入圆盘中央，才能开启超自然之界的通道。<br/>
不过，只有M对宝石之间可以互相传递能量，其中第i对宝石之间无论传递多少能量，都要花费Ti的代价。探险队员们想知道，最少需要花费多少代价才能使所有宝石的能量都相同？</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行两个整数N、M。<br/>
第二行N个整数Ai。<br/>
接下来M行每行三个整数pi,qi,Ti，表示在编号为pi和qi的宝石之间传递能量需要花费Ti的代价。数据保证每对pi、qi最多出现一次。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
输出一个整数表示答案。无解输出Impossible。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
50 -20 -30<br/>
0 1 10<br/>
1 2 20<br/>
0 2 100<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">30<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"> <br/><br/>
对于 100% 的数据，2&lt;=N&lt;=16，0&lt;=M&lt;=N*(N-1)/2，0&lt;=pi,qi&lt;N，-1000&lt;=Ai&lt;=1000，0&lt;=Ti&lt;=1000，∑Ai=0。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize11">Poetize11</a></p></div>

