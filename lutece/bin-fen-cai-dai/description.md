
# Content

陈队长妹纸的生日快要来了，陈队长作为一名`ACM`界知名选手自然会选择不一样的方式来给妹纸过生日，于是机智的陈队长为了不动声色显示自己的机智，选择了缤纷彩带作为庆祝之用。

![title](/source/lutece/bin-fen-cai-dai/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTAyMi8yMDE0MTIxMzAwMzE1OTQ3NjEwLmpwZw==.jpg)

在每一次操作，玩家选择任意一个给定的颜色然后选择一个未被选中的行或者未被选择的列并将对应颜色的彩带覆盖其上，最终每个格子被且仅被一个横条和一个竖条覆盖。如果最上面彩带的颜色要求与格子的颜色（如果格子被涂色）相同，那么游戏结束。

![title](/source/lutece/bin-fen-cai-dai/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTAyMi8yMDE0MTIxMzAwMzIxNzA2NzExLmpwZw==.jpg)

在一个下午和妹纸的愉快玩耍过程中，喜欢突破的陈队长萌发了改变规则的想法。如果每次插入的彩带不是放在原来已有的彩带之上，而是放在原有彩带之下，那么解决方案又是如何？当然，陈队长是一个好人，为了让问题变得简单，只要字典序最小的方案就足够了。

# Standard Input

第一行包含一个正整数$T（T \leq 50）$表示数据组数。

对于每组数据，第一行包含一个正整数$n（n \leq 1000）$，表示所给格子是$n \times n$的。

接下来的n行每行包含n个字符，每个字符表示一个格子的涂色情况（字符`0`表示该格子没有被涂色，大写字母`A`-`Z`表示$26$种不同的颜色，没有其他字符出现）

数据保证是合法的且有解的。

# Standard Output

每组数据包含$2 \times n$行，每行以$w$ $x$ $c$（$w$只能是字符`R`或者`C`表示选择的行或者列，`R`表示行，`C`表示列，$x$表示所选行或者列的编号，$c$表示所选颜色）表示一个操作，对于两个操作他们的字典序直接决定于$w$ $x$ $c$的字典序。

输出的要求是按照游戏操作顺序输出，并且字典序最小的。

每组数据最后输出一个空行。

  关于字典序，直观上就如同在字典中排列单词一样排序，按照字母表或数字表里递增顺序的排列次序，即先考虑第一个“字母”，在相同的情况下考虑第二个“字母”，依此类推。假设$a=a\_1a\_2\cdots a\_n$和$b\_1b\_2 \cdots b\_n$是集合${1,2, \cdots ,n}$的两个排列，字典序下$a$在$b$的前面，如果$ a\_1 < b\_1$ 或$a\_1 = b\_1$且$a\_2 < b\_2$，或$a\_1 = b\_1$且$a\_2 = b\_2$且$a\_3 < b\_3 \cdots $或$a\_1 = b\_1$且$a\_2 = b\_2$且$\cdots$且$a\_k = b\_k$且$a\_{k+1} < b\_{k+1}$，或$\cdots$，依此类推。

对于本题$a\_k > b\_k$只要满足下面$3$条之一即可
1. $w\_a > w\_b$
2. $w\_a = w\_b$且$x\_a > x\_b$
3. $w\_a = w\_b$且$x\_a = x\_b$且$c\_a > c\_b$

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
3
YBY
YGG
YR0
2
P0
YG
</td><td>C 1 Y
R 2 G
C 3 Y
R 1 B
C 2 R
R 3 A

C 2 G
R 1 P
C 1 Y
R 2 A

</td></tr></table>


# Constraints



# Note



# Source


