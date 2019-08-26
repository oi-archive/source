
# Description

<div class="content"><div>
<div>八云紫的式神八云蓝有一张符卡名为[式神-前鬼后鬼的守护]，这张符卡的弹幕为BOSS从两侧向自机发射大玉，大</div>
<div>玉后面跟着一些小玉，形成一个“V”字型的弹幕。然鹅兰大人觉得这个弹幕还能再美观一些，她想让自己的弹幕</div>
<div>能从左向右发射，于是她就开始了行动。</div>
<div>[式神-前鬼后鬼的守护]由 N波弹幕组成，每波弹幕都有一个落到板底的位置，第i波弹幕的落地位置为Xi。</div>
<div>为了让弹幕能从左到右落地，蓝妈需要改变一些弹幕的落地位置，使得改变后的落地位置的坐标不递减，即</div>
<div><img src="source/bzoj/5059/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcxMC8xMS5wbmc=.png" width="287" height="54" alt=""/></div>
<div>。然鹅改变弹幕的方向是很累的，蓝妈每将一波弹幕的坐标增加或减少1，就会花费一单位的能量，即</div>
<div><img src="source/bzoj/5059/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcxMC8yMi5wbmc=.png" width="237" height="54" alt=""/></div>
<div>蓝妈想确定一个最终的修改方案使得他花费的能量最少，于是她将设计修改方案的任务交给了自己的式神八云橙。</div>
<div>这可急坏了我们的橙喵，她只是连曼哈顿距离都不会算的年幼式神，你能帮助她完成这个任务吗？</div>
</div>
<p></p></div>

# Input

<div class="content"><div>输入文件第一行为一个正整数N ，意义如题目所示。接下来一行N个正整数，第i个整数代表Xi 。</div>
<div>N&lt;=5*10^5,Xi&lt;=10^9</div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数，为最小消耗的能量值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 3 2 4 5 3 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
将第二波弹幕的落地位置由3改为2 ，花费为1 ，将第六波由3 改为5 ，花费为2 ，总花费为1+2=3 ，形成了一个<br/>
不下降序列：1,2,2,4,5,5,9为最优解（不一定为唯一最优解）<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

