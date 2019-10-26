
# Content

有一天silentsky和lcy同学去教室上自习。silentsky百无聊赖地看着书本，觉得很无聊，看着右手边的lcy认真仔细的在画着她繁重的物理实验报告的图。silentsky无聊地弄着他的脉动瓶子，结果一不小心就把瓶盖弄到了lcy刚画好的坐标纸上，而且冥冥之中仿佛有一双手在安排，瓶盖的中心正好和坐标纸的中心重合了，瓶盖的边缘有水，会弄湿坐标纸的。 lcy很生气，后果很严重。

于是，lcy由此情形想出了一道难题问silentsky,如果他回答正确了。lcy就原谅了silentsky并且答应他星期天去看暮光之城2的请求，不然一切都免谈。然后silentsky就回去面壁思过了，现在silentsky好无助的，希望得到广大编程爱好者的好心帮助。

问题是这样的: lcy现在手上有一张$2n \times 2n$的坐标纸，而silentsky的圆形瓶盖的直径正好有$2\times n-1$大，现在lcy想知道 silentsky到底弄湿了多少个坐标纸的格子（坐标纸是由$1\times 1$的小格子组成的表格）

如果还是有人觉得理解不了焦急的silentsky的意思。干脆silentsky做下翻译，毕竟silentsky还是多了解lcy的O(∩_∩)O~。

问题就是给你一个$2n\times 2n$的正方形格子，分成$1\times 1$的格子，然后以中心为原点画一个直径为$2n - 1$的圆，问圆的周线穿过了多少个格子。

![.*](/source/lutece/yue-hui/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU2LzIwMTQwMjAyMjIwNDE0OTU4MTkucG5n.png)

# Standard Input

含有多组测试数据，每组数据都包含一个正整数$n$（$n\leq 1000$）。

当$n = 0$的时候结束程序，证明silentky经受住考验了的O(∩_∩)O~

# Standard Output

对于每个$n$，输出被瓶盖边缘的水弄湿了的格子数为多少。

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
<tr><td>1
2
0</td><td>4
12</td></tr></table>


# Constraints



# Note



# Source


