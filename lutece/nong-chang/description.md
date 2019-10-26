
# Content

现在很多人都喜欢玩QQ 农场。当然，我想你也不例外。

你是不是觉得QQ 农场给的地太少了呢？那你就来ACM农场吧！这里可以给你多达$1000\times 1000$的土地让你去尽情地耕作！

土地一下子变多了也会让你感觉很无聊啊！在一次大丰收后，你在地里零星地种了点稀有植物，然后就去YY去了。有了这么多的地，光在这里种地得经验是不是很浪费呢。于是，An idea comes up to you! 为什么不用这片地来做些什么研究呢？是不是会很有意思呢？

但在你做出行动之前，你想先测试一下效果如何。于是，你想先在一片$A\times B$矩形地里种一种同样的植物测试一下效果怎么样，你突然发现，由于你之前零星地种了一些稀有植物，虽然你也可以挖掉那些稀有植物，但由于这些植物种子是千载难逢的，你并不想这样做，于是你就得选择一下在哪里种了。你现在想知道在这片地里有多少种方法在一块没有在之前被种稀有植物的$A\times B$大小的土地上种这种同样的植物。

图中给出了现在农场的情况。

![title](/source/lutece/nong-chang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzAyLzIwMTQwNDA5MjE1MTE2OTUyNy5qcGc=.jpg)

在ACM农场，我们将给你$r\times c$的一片矩形土地，现在你已经在某些地上种了稀有植物。你事先做了$p$条记录，你记录了那些种了植物的点的坐标$(x, y)$ ，但由于疏忽你可能重复记录了某些点，但可以确定的是你已经全部记录下来了，于是你决定让电脑来帮你做计算。

# Standard Input

第一行是测试数据组数 $T$ ($1\leq T\leq 10$)。接下来有$T$ 组测试数据。

每组测试数据第一行是四个整数，以如下格式给出：`r c p q`（$1\leq r\leq 1000$，$1\leq c\leq 1000$，$1\leq p\leq 1000$，$1\leq q\leq 10$）。

接下来的$p$行每行两个整数，以如下格式给出：`x y` ($1\leq x\leq r$，$1\leq y\leq c$)。

接下来的$q$行每行两个整数，以如下格式给出：`A B`($1\leq A\leq r$，$1\leq B\leq c$)。

每个字母代表的含义如题中所述。

# Standard Output

对于每组测试数据，第一行输出：`Case #C:`，$C$ 从$1$ 到 $T$ 。

然后输出$q$ 行，每行只有一个整数，对应一个提问的回答，即在这组数据中给定的$r\times c$土地中有多少种方法在一块没有在之前被种稀有植物的$A\times B$ 大小的土地上种这种同样的植物。

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
5 5 3 2
2 3
3 2
3 4
1 2
2 3</td><td>Case #1:
28
3</td></tr></table>


# Constraints



# Note

对于样例，如图所示，这里你有$5\times 5$ 的土地，你想要种一片$1\times 2$ 的区域。$(4,2)-(5,2)$ 和 $(5,4)-(5,5)$ 都是可以的. 但是 $(3,4)-(3,5)$ 是不可行的。

![title](/source/lutece/nong-chang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzAyLzIwMTQwNDA5MjE1MzU5NDE0OC5qcGc=.jpg)

# Source


