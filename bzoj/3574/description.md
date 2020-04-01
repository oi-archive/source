
# Description

<div class="content"><p><span style="font-size: medium">一天闲着无聊的小L找来了当前正火爆的游戏《炉石传说》来玩，但是怎么打怎么输，于是他大喊一声“我要抄卡组！”就找来了游戏传说组第一名的游戏高手小H的直播来看。<br/>
    但是小L家的网络技术还停留在拨号，看着直播画面又是卡顿又是花屏，他不给力的网络让他完全无法记录小H展示的给力的卡组。小L周围都是学霸没有人玩游戏想去帮他这个忙，但是学霸们热衷于讨论各种信息学问题。    于是他想到了一个方法：由于每次花屏的屏幕位置不一样，于是小H每次总能记录下卡组的一些部分，如果这样记录多次，不就有可能还原出小L想要的一个卡组么？但是存在的一个问题是，小H每次展示的卡组有可能不一样，所以他想知道他每次看直播抄下来几次的卡组碎片是否一致。    这样一来小H将他遇到的游戏问题抽象成这样一个学术问题让学霸（你）解决：</span><span style="font-size: medium;">&#39;*&#39;</span><span style="font-size: medium;">可以匹配任意长度个的字符</span></p>
<p><span style="font-size: medium"> （包含0个），问所有字符串是否两两匹配。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">    第一行包含一个正整数T，表示了数据组数。<br/>
    接下来包含T组数据：<br/>
    每组数据的第一行是一个正整数N，表示该组数据酌字符串个数。<br/>
    接下来N行，每行一个字符串，字符串仅包含小写字母、数字、通配符术。<br/>
</font></p>
<p><span style="font-family: Arial; font-size: 14px; line-height: 23.796875px;">注意:数据为UNIX格式，中间包含空行,你可以采用</span><span style="font-family: Arial; font-size: 14px; line-height: 23px;">逐字符读入的方式</span></p></div>

# Output

<div class="content"><p><font size="4">    输出包含T行，每行一个字母Y或者N，Y表示这组数据中所有字符串两两匹配，N表示这组数据中至少有一对字符串不匹配。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
2<br/>
1234567890*1234567890<br/>
1234567890a1234567890<br/>
2<br/>
1234567890*1234567890<br/>
1234567890*1234567890<br/>
2<br/>
1234*67890a1234567890<br/>
1234567890*1234567890<br/>
2<br/>
1234567890*1234567890<br/>
1234567890a12345*7890<br/>
2<br/>
1234567890*1234567890<br/>
*12345<br/>
2<br/>
12345*67890<br/>
1234567890*1234567890<br/>
2<br/>
1234567890*1234567890<br/>
12345*<br/>
2<br/>
1234567890*1234567890<br/>
*67890<br/>
2<br/>
67890*<br/>
1234567890*1234567890<br/>
2<br/>
1234567890*a*1234567890<br/>
1234567890*1234567890<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Y<br/>
Y<br/>
Y<br/>
Y<br/>
N<br/>
Y<br/>
Y<br/>
Y<br/>
N<br/>
Y<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">    对于100%的数据，满足N&lt;= 100000，T= 10，输入文件不超过10M，N×最长字符串长度不超过2x10^8<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢NanoApe重新制作数据">鸣谢NanoApe重新制作数据</a></p></div>

