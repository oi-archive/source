
# Content

一天, 小C和小D一起观看了一个电视节目, 名字叫做: 《最强大佬》.

节目上面当时正在进行一个叫做 "数字华容道" 的游戏.

![c](/source/lutece/zui-qiang-da-nao/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTg0Ni8yMDE4MDMwMzE1MzUxODQ2MTEwLmpwZWc=.jpeg)

数字华容道是怎么玩的呢? 
1. 给出一个$4\times 4$的矩阵, 矩阵中有$\{1, 2, \cdots, 16\}$ 这些数字中的每一个数字恰一个.
2. 需要玩家通过移动矩阵中最大的那个数(当作华容道中的空白)来使矩阵获得顺序, 比如:
![a](/source/lutece/zui-qiang-da-nao/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTg0Ni8yMDE4MDMwMzE0MjA1MDU2NTYuanBlZw==.jpeg)
当然, 移动只能是上下左右四个方向.
3. 刚刚开始的时候, 矩阵中的位置是没有任何规律的, 但是保证一定有解, 比如:
![b](/source/lutece/zui-qiang-da-nao/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTg0Ni8yMDE4MDMwMzE0MjEwNTc3OTcuanBlZw==.jpeg)

小C听完玩法之后翻了一个白眼, 说: 这不是很简单吗? 我上我也行啊!

看着如此狂妄的小C, 小D当场就给他出了一个题:

将电视节目中的华容道推广到$n\times 4$的情形($2 \leq n \leq 20$).

请你编写一个程序, 给出一个能够完成这个华容道的可行的解, 步数小于1e4步.

小C听完了问题之后微微一笑, 然后将问题甩给了你.

# Standard Input

第1行:有一个正整数n($2\leq n\leq 20$)

第2~n+1行:给出了一个$n\times 4$的矩阵, 其中第$i$行$j$列表示题目中的华容道的第$i-1$行$j$列.

# Standard Output

一行, 表示可以使华容道复原的一个操作序列. (包含'h', 'j', 'k', 'l'四个字符的一个字符串) 其中:

'h'表示将白块左移1个位置(列号-1).

'j'表示将白块下移1个位置(行号+1).

'k'表示将白块上移1个位置(行号-1).

'l'表示将白块右移1个位置(列号+1).

(用单个字母比较节约空间, 而且使用vim的同学也应该对这四个字母不太陌生)

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
1 2 3 8
5 6 7 4</td><td>j</td></tr></table>


# Constraints



# Note



# Source


