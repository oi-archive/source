
# Content

[上一集](https://acm.uestc.edu.cn/problem/di-liu-zhang-zui-zhong-jue-zhan/description/)

# 终章: 真正的字符串

「晚上好，糖。」狗用钥匙打开了糖家的门。

![OIP.jpg](/source/lutece/zhong-zhang-zhen-zheng-de-zi-fu-chuan/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMTcvUDRUS2pnR2RMbnQ4WDNFLmpwZw==.jpg)

「晚上好。」

在监狱中的战斗。终归以糖的胜利告终。但是已经失去的编译器，再也安装不回来。当年的四大神兽，现在都只是普通人而已了。

大括号换行派的那三兄贵，在不敌糖之后也不见了踪影。但是糖已经不想追他们了。她只想在这个小镇上，当一个普通的美少女，过平静的生活。

「狗，对不起，当初我被马。。」

「没事，你知道的，无论我怎么样，只要你开心，我就满足了。」

「我只想做一个普通人。毕竟，爸爸妈妈给我起糖这个名字，就是希望我以后能甜甜蜜蜜地过下去。」糖回忆起了以前和父母的一些时光。

----
接下来是 if 线， if 线的内容会在队内赛里有延伸（主要是不加点东西不好引入题目）

「嗯？不对吧。我记得你当初明明说你自己没有名字。糖是我给你起的名字。」狗扭过头看向她。

「怎么会是你起的呢？怎么可能会有人出生还没有名字啊。」

糖笑了笑，然后笑容逐渐僵住了。

「怎么会。。。」糖突然用手抓住头。

「不对。。。不对！！！」

糖突然驱动码力打破窗户飞了出去。

早已没有码力的狗并没有办法追上去，踉跄了几步之后，站在窗边，看着糖远去的方向。

「怎么回事，你又要离我而去了吗？」

狗虽然嘴上说着不需在乎自己，但内心总归还是有对完美结局的向往的。而此时这个完美结局又笼上了一层迷雾。

「果然，舔狗是没有未来的。」

狗的大热的天浑身冰冷，眼泪不争气地流了下来。

糖驱使着码力来到了一片陌生的地方。虽然是陌生的地方，但是又很熟悉。糖突然感觉自己好像明白了什么。

「不会吧。。。」

糖原本清明的眼神中逐渐染上浑浊的颜色。

「这些都是假的。。。」

糖随手一挥，便是数百万的字符汇聚在一起。

「我现在到底在第几层？」

其实糖早已经参透了真正的字符串，并且在区域码力大会上夺得冠军。但是，但是，但是！

她现在对于过去的认知完全被扭曲了。

「刺客们，现身吧。」

「是！女王殿下！」

刹那间数十个刺客排成一排单膝跪地在糖的面前。

「果然。。。这里真的是假的。」

糖苦笑了笑。

随后，眼神中不再有一丝感情。

「我可还记得那个问题」

![OIP _1_.jpg](/source/lutece/zhong-zhang-zhen-zheng-de-zi-fu-chuan/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMTcvQ3RhbFZmRnBiVWo3QXMzLmpwZw==.jpg)

「我一直在思考字符串的模糊匹配，而模糊的匹配反噬了我自己，最后我的世界开始扭曲了。但是，再次经过了这么久的修炼，我明白了。今天，我就要给这个问题一个结尾。」



给出一个 $1$ 到 $26$ 的全排列 $p$。定义 $\text{id}(c)$ 为字符 $c$ 在小写字母中的顺序。 比如 $\text{id}(\text a)=1,\text{id}(\text b)=2,\text{id}(\text z)=26$。

给出两个串 $s$ 和 $t$ ，定义 $s$ 串和 $t$ 串的一个长度为 $|s|$ 子串 $t'$ 相等，当且仅当：

- $\text{id}(s_i)=\text{id}(t'_i)$
- $p_{\text{id}(s_i)}=\text{id}(t'_i)$

对于 $\forall i\in[1,|s|]$ 至少有一个命题成立。

对于 $t$ 的所有长度为 $|s|$ 的子串，检查它是否与 $s$ 相等。

# Standard Input

第一行 $26$ 个数字，代表全排列 $p$；
第二行一个串 $s$；
第三行一个串 $t$。

# Standard Output

输出一个 $01$ 串，第 $i$ 位为 1 代表 $t$ 从左到右第 $i$ 个子串与 $s$ 相等。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2 3 1 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26
abc
abcaaba</td><td>11001</td></tr></table>


# Constraints

$2 \leq |s| \leq |t| \leq 2\times 10^5$
保证 $s$ 和 $t$ 只由小写字母组成。

# Note



# Source


