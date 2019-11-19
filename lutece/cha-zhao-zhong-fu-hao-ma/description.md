
# Content

John有时候喜欢用手机键盘的字母来记电话，他觉得这样更直观易记。比如他拨打`310GINO`来向Gino's订一份pizza。

电话号码的标准格式是七位十进制数，手机键盘提供了从字母到数字的对应，关系如下：
* `A`, `B`, 和`C` 映射到 `2` 
* `D`, `E`, 和`F` 映射到 `3`
* `G`, `H`, 和`I` 映射到 `4`
* `J`, `K`, 和`L` 映射到 `5`
* `M`, `N`, 和`O` 映射到 `6`
* `P`, `Q`, `R`, 和`S` 映射到 `7`
* `T`, `U`, 和`V` 映射到 `8`
* `W`, `X`, `Y`和`Z`映射到 `9`

经过一段时间，John的电话簿上记录了很多电话号码，有的号码中含有英文字母，有点纯由数字构成。现在从电话簿中任取一个号码，John想知道电话簿中是否有号码与它重复。输出时先转换为标准格式，再输出重复次数，之间有一个空格。

# Standard Input

第一行是整数$N$，表明随后是由$N$行电话号码构成电话簿。紧接着一行是整数$T$，表明后面有$T$组测试数据，每组数据（电话号码）占一行。其中，每个电话号码有$7$位，$10\leq N\leq 1000$，$1\leq T\leq 100$。

# Standard Output

对应每组输入数据，输出一行结果。

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
<tr><td>12
704E457
12CS32W
568W941
3KP847P
1852Y28
590FMNM
3578477
K68R382
FT8YS65
2F3C067
A20O0F7
3889765
3
704E457
3889765
568W941</td><td>7043457 1
3889765 2
5689941 1</td></tr></table>


# Constraints



# Note



# Source


