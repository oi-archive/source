
# Content

你知道吗，小明的舅舅是有名的科学家！小明经常在电视上看到舅舅被一大群拿着黑色短棍子的人围着，妈妈说，那是记者们在采访舅舅。小明生日这天舅舅虽然没有来，可是却送来了一个很神秘的礼物。

咦，一个哑铃状的装着红色沙子的玻璃管子固定在木头架子上，这是什么东西呢？妈妈说，这个东西叫“沙漏”，是很久很久以前人们用来算时间用的。可是妈妈却没有说人们是怎么用它来算时间的。于是小明开始了研究。

![.*](/source/lutece/kuai-kuai-gao-su-wo-shi-jian/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTY5LzIwMTQwMjAyMjMwNjAyOTEyMjgucG5n.png)

小明发现沙漏玻璃管的两端很大，而中间却很小。把沙漏竖着立起来的时候，上面的沙子会顺着中间的小洞“流”到下面去。小明猜想，上面的沙子流下来是需要时间的，那么很久很久以前的人们肯定就是数下面的沙子然后算出时间了的，可是小明怎么也找不到这个玻璃管子的开口处，所以没办法来数沙子，那到底该怎么算时间呢？

小明想到了去年舅舅送了他的那根尺子，当时舅舅还教了小明怎么用它来量东西呢！小明把沙漏底部的沙子摇平了，然后测出了沙子的高度。小明觉得这个高度应该就可以用来算出时间了，可是他不会算，请问你会吗？

假设小明可以把沙漏下部的沙子完全摇平，即沙子构成一个上下底面平行的锥台。另外，假设小明能准确测量出平台的高度即平台上下底面的距离。

![.*](/source/lutece/kuai-kuai-gao-su-wo-shi-jian/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTY5LzIwMTQwMjAyMjMwNjMxODI0MjkucG5n.png)

假设小明的沙漏是由两个高度为$H$，底面半径为R的圆锥体玻璃管竖直对接而成，即两锥体的底平面平行且顶点重合。同时，假设任何时候沙子从沙漏上部到达下部的用时相同，设单位体积（$1$立方毫米）的沙子下落所需要的时间为$0.20s$。

# Standard Input

输入的第一行是$T$（不超过$3000$）。$T$表示测试部分的个数，每一部分都要求单独计算并按照要求输出结果。接下来是每一行为一个测试部分。每一行为$H$, $R$, $h$，分别表示沙漏圆锥体的高度H以及底面半径$R$，小明测得的沙漏下部沙子锥台的高度的$h$。$H$、$R$为整数，$h$都是浮点数且$h\leq H$。$H$、$R$、$h$的单位都为毫米。

# Standard Output

对于每个测试部分，请以$s$为单位输出构成小明所测的沙子平台所需要的时间，小数点后保留两位。为避免不必要的错误，请尽量使用double。请使用正确的方法以减小浮点运算中出现的精度误差。

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
<tr><td>5
50 50 0.000000
50 50 1.000000
50 50 25.000000
50 50 30.000000
50 50 50.000000</td><td>0.00
1539.59
22907.45
24504.42
26179.94</td></tr></table>


# Constraints



# Note



# Source


