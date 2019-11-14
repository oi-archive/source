
# Content

酱神来到了一座小岛，岛上有$n$个箱子。

一共有$3$中不同的钥匙，金钥匙、银钥匙和万能钥匙。酱神一开始有$a$把金钥匙、$b$把银钥匙和$c$把万能钥匙。

第$i$个箱子上有$xi$把金锁，$yi$把银锁。金钥匙只能打开金锁，银钥匙只能打开银锁，万能钥匙两种锁都能打开。用于打开锁的钥匙会立刻损坏，酱神会丢掉损坏的钥匙。箱子里有$ai$把金钥匙、$bi$把银钥匙和$ci$把万能钥匙，想要取出箱内的钥匙必须要打开这$xi+yi$把锁。

酱神的目的是使他拥有的钥匙总数最多。一旦酱神认为自己已经拥有了最多的钥匙，他就不会去开剩下的箱子了。

# Standard Input

第一行一个数$n$。

接下来有$n$行。每行$5$个数，$xi,yi,ai,bi,ci$。

最后一行3个数$a,b,c$。

$1=<n<=15$

$0=<xi,yi,ai,bi,ci,a,b,c<=10$

# Standard Output

输出一个数酱神的最多钥匙数。

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
<tr><td>3
1 0 0 0 1
2 4 0 8 0
3 9 10 9 8
3 1 2
</td><td>8
</td></tr><tr><td>1
0 0 1 2 3
0 0 0
</td><td>6
</td></tr></table>


# Constraints



# Note

第一个样例中酱神会打开第一个和第二个箱子。

# Source


