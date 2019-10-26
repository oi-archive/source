
# Content

totalfrank，rectaflex，silentsky，frost和allenlowesy都是PES（Pro Evolution Soccer）的忠实玩家，他们经常较量PES并且互有胜负。根据通用的联赛积分规则，allenlowesy想知道排名情况，这个任务交给你了。

![.*](/source/lutece/uestcguan-jun-bei/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTY4LzIwMTQwMjAyMjMwMTEzNTQ3MjcuanBn.jpg)

积分规则如下：
1. 每场比赛获胜方得$3$分，失利方得$0$分，打平则各得$1$分。
2. 当多位选手积分相同时，则净胜球多的选手排在前面。（净胜球=进球总和 - 失球总和）
3. 当多位选手积分相同且净胜球相同时，进球数多的选手排在前面。
4. 当多位选手积分相同、净胜球相同且进球数相同时，这些选手分享同一个排名。

# Standard Input

首先是数据组数$T$

对于每一组数据

第一行是两个数$N$（$N\leq 20$）和$M$($M\leq 300$)，分别表示有$N$位选手和$M$场比赛。

首先是$N$行输入，每行为一个选手的姓名，姓名长度不超过$15$，仅由大写和小写字母组成

接着有$M$行输入 每一行的格式为
```
name1 goal1 ：goal2 name2
```

表示`name1`选手与`name2`选手的比赛结果是`goal1:goal2`

goal和lose保证在int范围内

每个Player最后的进球数和丢球数保证在int范围内

# Standard Output

按照积分规则的排名输出排名表，每一列为
```
排名 选手姓名 积分 进球数 丢球数 净胜球数
```

当多位选手分享同一个排名时，在输出时按照字典序顺序输出。

每一列都要居中处理。输出格式请参照Sample Output和hint

每个test case后输出一个空行

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
</table>


# Constraints



# Note

1. 对要输出的每一列(排名，姓名，积分等)，若该列所有输出项中最长的长度为$L$，当前要输出的长度为$l$，则输出该项时，前面输出的空格数$\frac{L+2-l}{2}$，后面输出的空格数为${L+2-l+1}{2}$。如sample output1，Rank一列除去前后的`|`，最长是$4$格，而`|  1   |`中`1`只占据一格，则`1`之前输出$2$个空格，之后输出$3$个空格以使`1`居中。Pts一列有$5$格，`|  4  |`除去`4`只占一格还有$4$格，所以前面输出$2$个空格，之后输出$2$个空格。
2. 字典序：字符串从前往后依次比较，第一个字符不同的位置，字符较小的字符串字典序较小，详情参见字典。

# Source


