# 题目描述


<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【背景</span></b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">】<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">十七王魄聚齐，七大灵兽共同祈福，北半球精灵王约瑟横空出世……<img src="/upload/image/20141023/20141023135830_33048.jpg" alt=""/><span></span></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【问题描述</span></b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">】<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">约瑟，精灵王系，每天挑战两次（之后花费<span>RMB</span>购买挑战次数），战胜后获得精元，每天限量输出<span>12</span>个。（禽兽<span>s</span>：你到底说不说题？！）<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">约瑟挑战规则是消耗一次挑战次数进行一次判定，判定结果为<span>3</span>个灵兽和<span>4</span>种属性。若拥有所选中的三只灵兽，则只需挑战其余四只，（否则少哪就多打哪个），选中的四种属性中，若拥有对应王魄，即可在背包中携带该属性精灵（所以，约瑟难打是因为它限制了你的精灵选择……）。<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">如今，某赛尔<span>RP</span>爆发地抽中了战斗系，并且在前几天刚刚获得王之战魄，所以他带了库贝萨，利用反伤能力战胜约瑟。就在他挑战完四灵兽之后，问题来了，这个反伤的打法被和谐了<span>TAT</span>。（禽兽曰：特么有完没完了！）<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">呃，不急不急，快了。所幸他还可以带地面系，所以他还带了陶勒斯（桃乐丝？<span>NO</span>，是陶勒斯，地面系，以下简称陶牛）。现在只有靠它了……<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">可是，没有准备的小赛尔根本没有信心，可又不愿就此放弃，眼看着约瑟就在眼前，于是乎就找到你来帮忙。<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">现在他背包里准备了<span>N</span>个<span>HP+200</span>的恢复药剂，陶牛初始最大<span>HP</span>由文件给定。对战时，约瑟对陶牛的伤害设为<span>X</span>，<span>X</span>∈<span>[30,60]</span>（怎么这么少，因为陶牛附加了双防星魂，双防<span>+600</span>，为此他不知花了多少豆豆……），但是约瑟每三回合会使用必杀技，造成<span>200</span>点伤害（与x无关）；陶牛会首先进行<span>6</span>次攻击强化（即不进行攻击），六次强化后对约瑟的伤害设为<span>Y</span>，<span>Y</span>∈<span>[600,1000]</span>。约瑟<span>HP</span>我们固定为<span>1300000</span>！当然问题不会就只有这些，由于属性相克，精灵王系对除精灵王系外的所有属性都是<span>1.25</span>倍伤害，反过来自己算吧……<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:24pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">你的任务就是，判断这么多<span>HP</span>药剂够不够支持陶牛最终耗死约瑟（血药只有在约瑟即将打死陶牛时使用）。由于约瑟坑人的规则，陶牛不可以释放必杀技，否则会被约瑟一击造成π×<span>10000</span>的伤害。恢复<span>HP</span>永远是最先进行的，除此之外，每次都是约瑟先进行攻击。<span></span></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【输入数据格式】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:27.75pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">输入数据包含两行。<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:27.75pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">第一行为两个整数<span>N</span>和<span>HP</span>，表示<span>HP</span>药剂数量和陶牛初始最大<span>HP</span>值。<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:27.75pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">第二行为两个整数<span>X</span>和<span>Y</span>，意义如题。</span><span style="font-size:14pt;font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【输出数据格式】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:27.75pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">输出只一行。<span></span></span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:27.75pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">若药剂数足够，则输出最少需要的药剂数量，否则输出“<span>No</span>！”。</span><span style="font-size:14pt;font-family:微软雅黑, sans-serif;"></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【输入样例<span>1</span>】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:6pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">100 500</span> 
</p>
<p class="MsoNormal" align="left" style="text-indent:6pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">40 700</span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【输出样例<span>1</span>】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:6pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">No！<span></span></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【输入样例<span>2</span>】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;"> 200 400</span> 
</p>
<p class="MsoNormal" align="left">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;"> 40 600</span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【输出样例<span>2</span>】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left" style="text-indent:6pt;">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">No</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">！<span></span></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【数据范围及约定】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">对于<span>100%</span>的数据，<span>N</span>∈<span>(0,30000],HP</span>∈<span>(200,700)</span>。<span></span></span> 
</p>
<p class="MsoNormal" align="left">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">X</span><span style="font-size:12pt;font-family:微软雅黑, sans-serif;">和<span>Y</span>的范围见题目。<span></span></span> 
</p>
<p class="MsoNormal" align="left">
<b><span style="font-size:14pt;font-family:微软雅黑, sans-serif;">【提示】<span></span></span></b> 
</p>
<p class="MsoNormal" align="left">
<span style="font-size:12pt;font-family:微软雅黑, sans-serif;">题目冗长、仔细读题。<span></span></span> 
</p>
