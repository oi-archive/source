
# Content

天有异象，圣域生变，凡尘涂炭。这是一个不断勇攀高峰的故事，而这里，就是故事的起源。  
年轻的 ZXyang 被征召为勇者，踏上了拯救世界的旅途。 伟大的先知（毒奶） Vingying 戴着罩袍找到了 ZXyang ，向他轻声低语：“Winter is coming. 去吧，去那遥远的 Winterfall，找到北境之王 HeRaNO，然后打败他，拯救世界吧！”  
ZXyang 临危受命，决定召集天下能人义士，拯救风雨飘摇的大陆，踏上了永无止境的征程。后世称之为“燃烧的远征”。  
在远征路上，有一些魔法火炬，魔法火炬是一种神奇的魔法道具。它们固定在土壤中无法移动，而任何两个火炬，只要找到它们两个的中点，并且这个点到其中一个火炬的距离小于 $S$，就可以吸收 $1$ 点天地的灵气。而在同一个地方这样的火炬对数越多，能吸取的天地灵气就越多。  
但是 ZXyang 不可能为了吸收魔力就改变自己前进的脚步。所以，如果把远征的路径看成一条无限长的数轴，那么 ZXyang 只会选择在数轴上的整数点扎营，并且在这些营地处吸取天地灵气。所以， ZXyang 想要知道，给出 $n$ 个火炬的位置，在远征路上他一共可以吸取多少天地灵气。

# Standard Input

第一行两个整数 $n,S$ ($1 \leq n,S \leq 10^5$)。  
第二行**从小到大**给出 $n$ 个整数，第 $i$ 个数 $x_i$ 表示第 $i$ 个火炬的坐标 ($-10^5 \leq x_i \leq 10^5$)。数据保证 $x_i$ 互不相等。

# Standard Output

输出一行一个整数，表示他可以吸收多少天地灵气。

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
<tr><td>5 2
1 2 3 4 5</td><td>3</td></tr><tr><td>5 1
1 2 3 4 5</td><td>0</td></tr></table>


# Constraints



# Note

对于第一个样例，ZXyang在坐标为 $2,3,4$ 的地方驻扎时，可以各吸收 $1$ 点天地灵气。  
对于第二个样例，ZXyang不论在哪里驻扎，都无法吸收天地灵气。

# Source


