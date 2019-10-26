
# Content

iTunes是苹果公司于2001年推出的数字媒体播放器，这被看作是改变人们收听音乐习惯的软件。

pfctgeorge是一个酷爱音乐的GG，特别爱欧美音乐，而他经常使用iTunes里华丽丽的Cover Flow功能（如图）。pfctgeorge的iTunes媒体库中有$n$张专辑，为了简化问题，假设在Cover Flow中从左到右编号为$1\cdots n$。

![title](/source/lutece/cover-flow/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTM1LzIwMTQwODI1MjI1NTU2MTU3Ny5qcGc=.jpg)

现在，pfctgeorge很无聊，于是他发疯似地连按了一串左右方向键，然后有一张专辑会停在屏幕中央，于是他会播放这张专辑。请告诉他按了这一串方向键后他会听到哪张专辑？

注意：当移到达到Cover Flow的最左端时，再按左方向键时将不再移动；右端亦然。

# Standard Input

输入的第一行是一个整数$T$（$T\leq 50$），表示测试数据的组数。

对于每组数据，第一行是三个整数$n$、$m$、$t$（$1\leq n\leq 1000$，$1\leq m\leq 100$，$1\leq t\leq n$），分别表示资料库中专辑数、按键的次数和屏幕中央最初指向的专辑编号。

接下来的$m$行，表示依次按键的序列。每行只有两个字符，其中`|>`表示按的是右键，`<|`表示按的是左键。

# Standard Output

对于每组测试数据，输出一个整数$i$，表示pfctgeorge最终会听到第i张专辑。

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
3 3 2
|>
|>
<|
4 5 1
|>
<|
|>
|>
|></td><td>2
4</td></tr></table>


# Constraints



# Note



# Source


