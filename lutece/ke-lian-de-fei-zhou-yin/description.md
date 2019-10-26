
# Content

UESTC有一支阴阳师集训队，成员有以欧洲柱为首的欧洲人，和非洲银牌爷。除了非洲银，大家都有了SSR，在阴阳师的世界里叱咤风云，银牌爷不甘心做咸鱼，立志通过攒碎片的方式得到属于他的SSR。(阴阳师中共有6种SSR，分别是A，B，C，D，E，F，50个相同碎片可以换到对应的SSR)

众所周知，阴阳师中得到ssr碎片的方式有两种，一种是通过百鬼夜行，另一种是通过商城购买F的碎片，F的碎片每天可以从商城购买一个。由于我们有阴阳师内部人员，所以我们可以知道非洲银接下来N天能够通过百鬼夜
行得到的SSR碎片。

已知银牌爷会在第K天放弃阴阳师这款游戏（第K天还在玩），问在银牌爷放弃之前能否得到一只SSR。每日通过商城购买的F碎片不算在百鬼夜行得到的碎片中，即每日得到的碎片=F*1+百鬼夜行所得，由于银牌爷的迫切，每天上线他都会先去
商城买一个F碎片。

# Standard Input

第一行包括一个整数N(0<=N<=50)和一个正整数(1<=K<=50)，表示银牌爷第K天放弃游戏。接下来有N行，第i行表示第i-1天银牌爷
通过百鬼夜行得到的碎片种类，每一行包括一个字符串，字符串长度不超过100。

例：ABACF表示银牌爷得到了两个A碎片，一个B碎片，一个C碎片和一个F碎片。序列表示得到碎片的顺序。

# Standard Output

银牌爷在这K天能否得到一只SSR？如果能输出银牌爷得到第一只SSR的天数，和得到第一只SSR的种类，如果在放弃之前不能得到SSR输出"Feizhou Yin".**(如果在第K天得到也算作得到，如果同一天攒齐了两种SSR，则输出最先得到的SSR，N天之后银牌爷不再购买碎片)**,如果在N天后，银牌爷既没有SSR，也没有放弃阴阳师，则输出"AMNZ"。

**输出请不要包含引号，输出只含一行，Feizhou Yin和AMNZ不同时输出**

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
<tr><td>5 42
EFEAAECFFBDBFBCDADACDEEDCCFFAFADEFB
AFDCDDCDBFEFCEDDBFDBEEFCAAEECEECDCDE
ADDCDFAEACECFEADCBFECADFDFBAAADCFAFFCEADFDDAEAFAFFD
FECEDEEEDFBDBFDDFFBCFACECEDCAFAFEFAFCDBDCCBCCEADADAEBAFBACACBFCBABFDAFBEFCF
CFBCEDCEAFBCDBDDBDEFCAAAACCFFCBBAAEECFEFCFDEEDCACDAC</td><td>5 F</td></tr><tr><td>2 2
AB
AB</td><td>Feizhou Yin</td></tr></table>


# Constraints



# Note

**输出请不要包含引号，Feizhou Yin和AMNZ不同时输出**

# Source


