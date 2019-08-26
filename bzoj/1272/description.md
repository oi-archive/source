
# Description

<div class="content"><div>《基尔伽美修》是人类历史上第一部英雄史诗，两河流域最杰出的文学作品之一。作品讲述了基尔伽美修一生的传</div>
<div>奇故事。在动画Fate／staynight中，基尔伽美修与亚瑟王等传说中的英雄人物一起出现在了现实世界，展开了一</div>
<div>场惊天地、泣鬼神的战斗一·在记载于12块泥板的史诗中，基尔伽美修与同伴安吉杜一起降伏了森林的守护者——</div>
<div>神兽洪芭芭，成为地上最强的王者，同时将世间所有财宝收归手中。王之财宝(GateofBabylon)成为Fate中金皮卡</div>
<div>（基尔伽美修的外号…）炫耀的资本……一天金皮卡突发奇想：如果从自己无尽的财宝里面，随便抽不超过M件宝</div>
<div>具出来砸死敌人的话。一共有多少种搭配方法呢一一？假设金皮卡一共有N种不同类型的宝具，大部分类型的宝具</div>
<div>都有无限多，但其中T种超级神器的数量是有限的。设第i种超级神器的数量不超过Bi件。若相同类型的宝具数量相</div>
<div>同，则认为是相同的搭配方案。金皮卡知道方案数会很大，从小数学成绩就好的他挑选了一个质数P，请你帮他计</div>
<div>算一下方案数模P后的余数。注意，一件也不选也是一种方案。</div></div>

# Input

<div class="content"><div>第一行包含4个整数，分别为N，T，M，P</div>
<div>之后T行，每行一个鏊数，代表Bi</div>
<div>N，M≤10^9，P≤10^5，Bi≤10^9</div>
<div>0≤T≤N，M&gt;O，Bi&gt;0，T≤15</div></div>

# Output

<div class="content"><div>仅包含一个整数，即方案数模P后的余数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 10 13<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
【样例说明1】<br/>
只有一种超级神器，数量不超过3<br/>
当不选择超级神器时，另一种宝具可以挑选0到10件，共11种方案<br/>
当选择1件神器出来时，另一种宝具可以挑选0到9件，共10种方案<br/>
当挑选2件神器时，共9种方案<br/>
挑选3件神器时，共8种方案<br/>
一共有11+10+9+8=38种方案，38mod13=12，于是答案等于12<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

