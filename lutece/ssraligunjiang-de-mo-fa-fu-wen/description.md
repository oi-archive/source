
# Content

打dota总是在蓝猫与小鹿之间纠结不清的`SSRaligun`酱是学院都市里一名隐藏的$level5$能力者，他会使用$3$种基本魔法符文，并且能够制作多种魔法卷轴。在学院都市那终日不见阳光的ACM(Arch Chain Master)街上,`SSRaligun酱`拥有一家名叫`秋之月`的魔法卷轴商店。

不同的魔法卷轴需要不同的制作方法，所以制作一个魔法卷轴是很困难的，但是SSRaligun酱拥有一部如何制作魔法卷轴的秘术之书。(传说是一位名为`Icerain94`的顶级能力者赠送给`SSRaligun`酱的禁书)秘术之书通常把魔法卷轴视作为一个$1 \times n$的矩阵(从$1$开始编号)，然后执行$m$次填充操作,每次操作在$[l,r]$的区间上填充第$type$种魔法符文。

在魔法填充结束之后如果同一格被填入了多种符文，符文就会互相融合，形成新的符文，符文合成公式如下:

```
type1+type1=type1 type2+type2=type2 type3+type3=type3
type1+type2=type4 type4+type1=type4 type4+type2=type4
type1+type3=type5 type5+type1=type5 type5+type3=type5
type2+type3=type6 type6+type2=type6 type6+type3=type6
type4+type4=type4 type5+type5=type5 type6+type6=type6
type4+type3=type7 type5+type2=type7 type6+type1=type7
type4+type5=type7 type4+type6=type7 type5+type6=type7
type1+type2+type3=type7 type4+type5+type6=type7
type7+type1=type7 type7+type2=type7 type7+type3=type7
type7+type4=type7 type7+type5=type7 type7+type6=type7
type7+type7=type7
```

温馨提示：上述公式可以总结为基础符文形成二阶符文，二阶符文形成三阶符文，同属性高阶符文吸收低阶符文，同属性同阶符文吸收同阶符文。(相信我,理解这段话将大大缩短你的解题时间,而理解这些公式的内涵比你手工模拟公式的代码量要小很多)

现在我们知道了制作某个魔法卷轴所需要的$m$次步骤$l,r$和$type$，又萌又帅又可爱的SSRaligun酱一眼就看出了最后哪一种魔法符文的数量会最多，那么现在你能算出这种魔法符文是那种魔法符文吗？

# Standard Input

第一行为数据组数$T$,对于每一组数据,第一行为两个整数$n,m(0 < n,m \leq 2000)$,接下来$m$行每行共有三个整数$l,r,type(1 \leq l \leq r \leq n,1 \leq type \leq 3)$,分别表示魔法填充区域的左边界和魔法填充区域的右边界以及对应魔法符文种类.

# Standard Output

对于每一组数据输出一行,每一行行首为`Case`+`#`标号，然后输出数量最多的魔法符文的$type$(如果有多种符文数量都是最多的，则按照数字编号从小到大依次输出，详细见样例)。

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
<tr><td>2
6 3
1 3 3
1 2 2
1 1 1
10 2
1 5 2
6 10 3</td><td>Case #1: type3 type6 type7
Case #2: type2 type3</td></tr></table>


# Constraints



# Note



# Source


