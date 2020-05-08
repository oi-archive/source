
# Content

利姆露遇到了一个树人，现在她要解答树人的困惑才能从它那里得到自己想要的奖品，于是她把这个任务交给了大贤者，而大贤者希望你能帮忙解决这件事。

树人知道在空气中存在有 $n$ 种魔法元素，分属三类，可分别称为 a 类，b 类，c 类，三类元素之间的关系为：a 类克制 b 类，b 类克制 c 类，c 类克制 a 类。

树人想知道根据它的观测是否能知道想知道的元素间的关系。

树人对它观察到的元素间的关系以如下方式进行描述：
- $\texttt{1 x y}$：$x,y$ 号元素同类。
- $\texttt{2 x y}$：$x$ 号元素克制 $y$ 号元素。

给出全部观测后（保证观测间不冲突）树人开始以如下方式提问：
- $\texttt{q x y}$：单独输出一行用一个数字回答 $x$ , $y$ 号元素间的克制关系 ：$0$ 表示同类，$1$ 表示 $x$ 克制 $y$ ，$2$ 表示 $x$ 被 $y$ 克制，$3$ 表示未知。

但树人太老了，记忆力不是很好，所以它会边询问边从记录中检查是否出错，当发现出错时，它会给出提醒：
- $\texttt{del z}$：第 $z$ 次的描述可能是错的，请将这一条删去（出现重复删除时忽略）。

想要取得大贤者的认同，就请努力解决这个问题吧。

# Standard Input

第一行是三个用空格隔开的整数 $n,k,m$，分别表示元素种数，观测条数，询问和删去总次数。

接下来 $k$ 行是 $k$ 次观测的数据；

接下来 $m$ 行是 $m$ 次询问或删去。

# Standard Output

同询问次数行，每行一个整数表示答案。

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
<tr><td>3 3 5
1 1 2
2 1 3
2 2 3
q 1 3
del 2
q 1 3
del 1
q 1 3</td><td>1
1
3
</td></tr></table>


# Constraints

$0<n\le 10^5,0<k\le10^6,0<m\le10^6$

# Note



# Source


