
# Content

***“吾名布克罗里，红魔族首屈一指的鞋店老板之子，乃操纵上级魔法的大魔法师是也！”***
![](/source/lutece/hong-mo-zu-shou-qu-yi-zhi-noxie-dian-lao-ban-zhi-zi/img/aHR0cHM6Ly9maWxlcy5jYXRib3gubW9lLzh1d3UxZS5qcGc=.jpg)
布克罗里今天也无所事事地在红魔乡周围为了守卫红魔之里的四处乱逛。
然后布克罗里停在了村口的一棵树下。
众所周知，在这个美好的世界上，西瓜长在海里，而鱼一般种在田里。
这是一棵野生的沙丁鱼树。
树上长着许多沙丁鱼。
这棵沙丁鱼树由 $N$ 个节点构成，$1$ 号节点为树根，处于整棵树的最底部，在第 $i$ 个节点上有一条编号为 $i$ 的沙丁鱼。布克罗里站在树下看着树上的沙丁鱼，他发现了一个奇妙的事实：在第 $i$ 号节点的沙丁鱼只会跑到离 $i$ 号节点距离不超过 $L$ 的节点上去；并且沙丁鱼只会往上跑，即只会往 $i$ 号节点的子树上跑。
布克罗里想知道每条沙丁鱼可能跑到的节点个数。
但突然，布克罗里旁边的森林中闪过一个人影，是红魔族首屈一指的占卜师索凯特。于是对索凯特爱慕已久的布克罗里立刻追了过去。
而你，一个一般通过的红魔族，听到了布克罗里的问题。你决定解决这个问题，这样布克罗里家的鞋店可能会给你的新鞋打个折。

# Standard Input

输入共 $N$ 行。
第一行两个整数 $N$ 和 $L$，分别表示沙丁鱼树的节点个数和沙丁鱼的活动范围。
第 $i$ 行两个整数 $p_i,d_i$。$p_i$ 表示第 $i$ 号节点到 $1$ 号节点树根路径上最近的一个节点编号，即 $i$ 号节点的父亲。$d_i$ 表示 $i$ 号节点与 $p_i$ 之间的距离。

# Standard Output

输出 $N$ 行 $N$ 个整数，表示每个节点的沙丁鱼可能跑到的节点个数。

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
<tr><td>6 5
1 3
2 4
1 5
3 1
4 2</td><td>3
3
2
2
1
1</td></tr></table>


# Constraints

$1≤N≤200000,1≤L≤10^{18},1\le p_i<i,1\le d_i\le 10^{12}$

# Note



# Source


