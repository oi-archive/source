
# Content

beap已经两个月都没有上课了，至于你信不信，我反正是信了。这两个月来beap一直潜心学习《图论秘籍》。现在终于大功告成，于是他自诩向前五百年，向后五百年都没人能超过他，并且提出了“一切皆最小生成树”这个震惊世界的口号。

而beap从来不怕什么“长江后浪推前浪，前浪死在沙滩上”的风言风语，于是他自信的承诺，任何江湖新秀，只要解出下面这个问题，他便会授予《图论秘籍》这一神书。

在一个连通图$G$中，如果存在连通子图$G'$包含$G$中所有顶点和一部分边，且不形成回路，则称$G'$为图$G$的生成树，代价最小生成树则称为最小生成树（边权之和最小）。

很多时候，最小生成树的形态并不唯一，对于图中的边$e\_i$:若$e\_i$至少会在一棵最小生成树上出现，则称$e\_i$是可采纳边。

例如，对于样例：

![title](/source/lutece/lia-yue-mei-you-ke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjM0LzIwMTQwODI5MDAwMjU3MDA3MjguanBn.jpg)

现在，对于给定的连通图，需要你求出最小生成树的代价和可采纳边的个数。

# Standard Input

单组测试数据。

第一行为$n,m$表示图的顶点数和边数 ($1 \leq n \leq 10^5$, $n-1 \leq m \leq 10^5$)

接下来的$m$行，每行有三个整数$u,v,w$，表示无向边$(u,v)$的边权为$w$ ($1 \leq u,v \leq n$ , $-1000 \leq w \leq 1000$)。

# Standard Output

输出最小生成树的代价和可采纳边的个数。

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
<tr><td>4 5
1 2 101
1 3 100
2 3 2
2 4 2
3 4 1</td><td>103 4</td></tr></table>


# Constraints



# Note



# Source


