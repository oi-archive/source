
# Content

某日，喵哈哈村，天行廖大师走在咸鱼路上，突然，迎面走来一女子

有言到：

北方有佳人，绝世而独立。

一顾倾人城，再顾倾人国。

闭月羞花怨，沉鱼落雁愁。

貂婵拜月闭冰盘，佳丽忧民叹国残。

回眸一笑百魅生，六宫粉黛无颜色。

解释春风无限恨，沈香亭北倚阑干。

绝代有佳人，幽居在空谷。

君王数载犹尝胆，美色几时能救国?

俊眉修眼，顾盼神飞，文彩精华，见之忘俗。

脸若银盘，眼似水杏，唇不点而红，眉不画而翠。

手如柔荑，肤如凝脂，领如蝤蛴，齿如瓠犀，螓首蛾眉，巧笑倩兮，美目眇兮

咸鱼廖大师的目光已经呆滞，而更让他吃惊的是她的旁边居然是柱爷！![title](/source/lutece/zhu-ye-ba-mei-chi-liang-gao-qing-zhong-zhi-ban/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMyMi8yMDE2MDQyODIzMzcyMTA4MTI1LmpwZw==.jpg)

说好的一起单身，柱爷却悄悄的脱了单![title](/source/lutece/zhu-ye-ba-mei-chi-liang-gao-qing-zhong-zhi-ban/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMyMi8yMDE2MDQyODIzMzgwOTM5OTI2LmpwZw==.jpg)

当然，把妹柱把妹是需要资金的！，而股市正好是柱爷资金的主要来源地

这是因为柱爷有自己独特的黑科技技巧

柱爷通过交易知道了接下来$N$天的股市行情，每天的买入/卖出价格为$P\_{i}$，每天柱爷只能做最多一种操作，当然柱爷也可以什么都不做，对于每个操作，有一个手续费$F$，对于买入操作，会在买入操作之前扣除$F$块钱，而对于卖出操作，则会在柱爷卖出操作执行完后扣除$F$的手续费.

注意，柱爷初始时有$M$块钱的本金，柱爷需要保证在任意时刻自己的现金${\geq}0$

现在请问柱爷在$N$天后最多能有多少钱?

# Standard Input

第一行三个整数$N$，$M$，$F$，分别表示一共有$N$天，本金为$M$，手续费为$F$

接下来$N$行，每行一个整数$P\_{i}$，代表第$i$天的交易价格

数据保证:

*  $1 \leq N \leq 10^5$

*  $1 \leq M \leq {10^5}$

*  $1 \leq F \leq {10^5}$

*  $1 \leq P\_{i} \leq {2*10^5}$

*  $答案 \leq {2*10^{18}}$

# Standard Output

输出仅一行，表示柱爷$N$天后能拥有的最多现金

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
<tr><td>3 10000 1
4000
4004
4002</td><td>10006</td></tr><tr><td>3 10000 100000
4000
4004
4002</td><td>10000</td></tr></table>


# Constraints



# Note

对于样例$1$，柱爷会在第一天买入$2$股，在第$2$天卖出$2$股最优

这样柱爷能赚最多的钱（就能更好的把妹了）

# Source


