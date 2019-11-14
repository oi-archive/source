
# Content

娜兹玲可以操纵老鼠，并使唤它们找寻自己想要的东西。但是老鼠们并不是总是那么可靠，比如有一次它们带回了一本被咬的残缺的珍贵古书，而且里面还夹扎着一些其他书籍的碎片。幸运的是，娜兹玲知道稗田阿求有过目不忘程度的能力，而且阿求看过这本古书的一些片段。于是娜兹玲拜托阿求重写这本书。当阿求认为某一段文字可能是古书中的内容时，就会从脑内索寻出最合适的一段片段，那段文字是这一片段的某一连续部分时，阿求认为这段文字确实是古书的内容。现在阿求想知道这近半百段文字是否是古书的内容，你能帮帮阿求么？  

![title](/source/lutece/xiao-xiao-de-xun-bao-da-jiang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTM4LzIwMTQwODI1MjMxNjQ0MjA2OS5qcGc=.jpg)

![title](/source/lutece/xiao-xiao-de-xun-bao-da-jiang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTM4LzIwMTQwODI1MjMxNjQ4NzUzMTAuanBn.jpg)

# Standard Input

输入的第一行是一个整数t，表示有$t$段待辨识的文字。接下来每两行分别表示，待辨识的文字和阿求从记忆中索寻的对应文字。阿求虽然有过目不忘程度的能力，但是也不会去辨识和索寻超过千字的文字片段，这里假设这本书是以$26$个大写英文字母所写。

对于待辨识的文字是这样描述的，`?`表示该位上有一个不可辨认的字母，`*`表示此处有若干个待辨识的字母（可以是零个）

# Standard Output

如果该段文字确实出自古书输出`YES`，否则输出`NO`。

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
NOAK?UU*
HIEDANOAKYUU
ZRIN?
NAZRIN</td><td>YES
NO</td></tr></table>


# Constraints



# Note



# Source


