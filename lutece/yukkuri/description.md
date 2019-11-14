
# Content

油库里是幻想乡特有的一种生物。他们的身体仅有两部分：面皮构成的表皮和豆沙构成的内陷。 

![title](/source/lutece/yukkuri/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTM5LzIwMTQwODI1MjMyMTE2NTI4MTEuanBn.jpg)![title](/source/lutece/yukkuri/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTM5LzIwMTQwODI1MjMyMTIzMDU0MTIuanBn.jpg)

魔法森林中就生活着这样的成千上万只的油库里，当两只油库里发生战斗时表皮的质量会决定战斗的胜负，负者会死掉，胜者的皮会耗损掉等同于负者的皮质量的质量，当然如果两者皮的质量一样，那么同归于尽。。。然后接下来胜者会吃掉负者的内陷（= =），并把吃掉的部分中全部用于增长自己的表皮。 

由于质量特别的大油库里有机会成为dos油库里，所以现在我们很关心魔法森林中的油库里最大能长到多大。现在告诉你每只油库里的初始表皮和内陷质量，你能求出魔法森林中的一只油库里通过战斗最大能成长到多少的质量么？（假设除了考察的那只油库里之外，其他油库里之间不会发生战斗） 

# Standard Input

输入的第一行是一个整数$T$($T\leq 30$)，表示有魔法森林有$T$个区域，每个区域中的油库里是独立的，即不能对其他区域的油库里发生战斗。

对于每个区域，由$N+1$行来描述，第一行是一个整数$N$($1\leq N\leq 100000$)，该区域有多少只油库里，接下来有$N$行，每行有两个整数$u$和$v$($1\leq u,v\leq 10^9$)，代表这只油库里的表皮质量和内陷质量。

# Standard Output

对于个区域，输出油库里最后能够达到的最大质量。

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
2
1 2
2 1
3
1 2
2 3
2 1</td><td>4
6</td></tr></table>


# Constraints



# Note

在第一组样例中，$2$号油库里击败一号油库里后损失掉$1$单位质量的皮，并通过吃掉一号油库里的内陷，获得$2$单位质量的皮，最后$2$号油库里有$3$单位质量的皮，和$1$单位质量的内陷，所以最终质量为$4$。

# Source


